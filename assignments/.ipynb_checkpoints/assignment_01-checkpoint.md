# Working with Data and Visualization

John Tukey who coined the term Data Analysis in the 70s says **"The greatest value of a picture is when it forces us to notice what we never expected to see.”**

Exploratory Data Analysis and Visualization (EDAV) is the first step in your data analysis process. Exploring data, summarizing their main characteristics, often with visual methods helps us to form better questions.


For your first assignment, you will explore [**The Museum of Modern Art (MoMA) Collection**](https://github.com/MuseumofModernArt/collection) which has two datasets.

1. The Artworks dataset: contains represents all of the works that have been accessioned into MoMA’s collection and cataloged in their database. It includes basic metadata for each work, including title, artist, date made, medium, dimensions, and date acquired by the Museum. Some of these records have incomplete information and are noted as “not Curator Approved.”

2. The Artists dataset: contains 15,282 records, representing all the artists who have work in MoMA's collection and have been cataloged in our database. It includes basic metadata for each artist, including name, nationality, gender, birth year, death year, Wiki QID, and Getty ULAN ID.


The goal of this assignment is to allow you to work with data, explore it, and visualize it to tell a story. For example, you can describe the data, talk about the outliers, show interesting relationships between different features, and so on. There is no right or wrong answer so go crazy! :collision:


You are free to use any tool (**except for Excel** :poop:) to explore either dataset. I suggest using python especially if you haven't used it before. 



## How to submit?

Treat your repo similar to a folder on dropbox or drive and `push` any content you produced for your assignment. The content can be jupyter notebooks, jpg, etc.

Your submissions should be self-explanatory on their own. Imagine you are publishing an article and your audience doesn't have access to you to ask any questions. To do so, you can:

* If you are submitting a `notebook`, you can have `markdown` cells (as oppose to `code`) which you can use to explain anything you like.
* If you are **not** submitting a `notebook`, make sure you update the `readme.md` file with any explanations you think is necessary.

There are many resources on good practices of organizing your git repos(like [this](https://github.com/drivendata/cookiecutter-data-science)). A simple standardized structure is like:

```
├── README.md          <- The top-level README for this project.
│
├── data               <- All raw and processed data goes here.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── img                <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
                          generated with `pip freeze > requirements.txt`

```
