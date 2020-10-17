# Assignment 03 - Hyperparameter tuning + Unsupervised learning


## Description

This assignment has two sections. Each section has multiple parts with their respective point in parentheses. 

* First part is to build on what you have already done for **assignment 02**. You should pick your non-linear model from assignment 2, then use an **[imputation](https://scikit-learn.org/stable/modules/impute.html)** method to handle missing values and run a grid search to tune your model's hyperparameters(25%). You should report the accuracy of the best set of parameters(5%). Finally, you should describe the precision/recall of your top-performing model using both the precision-recall curve and the confusion matrix (25%).

* The second part is an unsupervised learning problem. We are using a real-world dataset to perform clustering. These data contain gene expression values from a manuscript authored by The Cancer Genome Atlas (TCGA) Pan-Cancer analysis project investigators. The [dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/00401/TCGA-PANCAN-HiSeq-801x20531.tar.gz) is available from the [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/gene+expression+cancer+RNA-Seq), but you can use the Python code in the next section to obtain the data programmatically.

Like the previous assignment, you should start with preprocessing and data cleaning (including checking the distribution of numeric features, count of categories in categorical features, handle non-valid values, and use **[LabelEncoder()](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html)** to convert target labels to integers) (15%). The next step is to create a pipeline to scale your data and reduce the dimension of the features to 2, using (10%) and use K-Means clustering algorithm (10%). You should find the appropriate number of clusters using either **The elbow method** or **The silhouette coefficient** and visualize the result(15%).

## Gene Expression Cancer RNA-seq Data Set


    ```
    import tarfile
    import urllib
    import numpy as np
    import pandas as pd

    uci_tcga_url = "https://archive.ics.uci.edu/ml/machine-learning-databases/00401/"
    archive_name = "./data/TCGA-PANCAN-HiSeq-801x20531.tar.gz"
    
    # Build the url
    full_download_url = urllib.parse.urljoin(uci_tcga_url, archive_name)
    
    # Download the file
    r = urllib.request.urlretrieve (full_download_url, archive_name)
    
    # Extract the data from the archive
    tar = tarfile.open(archive_name, "r:gz")
    tar.extractall()
    tar.close()


    datafile = "./data/TCGA-PANCAN-HiSeq-801x20531/data.csv"
    labels_file = "TCGA-PANCAN-HiSeq-801x20531/labels.csv"

    data = np.genfromtxt(
        datafile,
        delimiter=",",
        usecols=range(1, 20532),
        skip_header=1
    )

    true_label_names = np.genfromtxt(
        labels_file,
        delimiter=",",
        usecols=(1,),
        skip_header=1,
        dtype="str"
    )
    ```


The data variable contains all the gene expression values from 20,531 genes. The true_label_names are the cancer types for each of the 881 samples. The first record in data corresponds with the first label in true_labels.

The labels are strings containing abbreviations of cancer types:

* BRCA: Breast invasive carcinoma
* COAD: Colon adenocarcinoma
* KIRC: Kidney renal clear cell carcinoma
* LUAD: Lung adenocarcinoma
* PRAD: Prostate adenocarcinoma



## Submission
Make sure your notebook is formatted, commented, and has enough written information for anyone to follow your process (use markdown cells). Similar to the previous assignment, follow the suggested folder structure.


## Other remarks
Please note that there a few new steps (Imputation, LabelEncoder, Evaluation methods for clustering) that we haven't explicitly discussed in the class. However, we have talked about similar steps/concepts. I'd like you to read about these new methods and try to implement them. As always, feel free to ask questions on canvas or reach out to me directly.

---
#### code of conduct

* Your answers to this assignment must be your own work.
* You may use Google, Stack OVerflow, etc but do not search for solutions to the overarching problem we're asking you to solve.
* You may not share your solutions with anyone else. This includes anything written by you, as well as any official solutions provided by Lazard.
* You may not engage in any other activities that will dishonestly improve your results or dishonestly improve or damage the results of others.
