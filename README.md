# Machine Learning Course
**INFO 656-01 - Fall 2020**

### Course Description:

Machine learning is a rapidly growing field that develops algorithms for tasks such as data classification and prediction. These algorithms are programmed to operate and adjust themselves independently of human intervention (i.e., to learn), allowing data work to occur quickly and at scale. Machine learning is a key technology behind the automation across many social areas today, often branded AI.

This course offers an introduction to machine learning as a practical tool that we can use, and as a technological field with social implications. We will learn about key concepts in machine learning; survey a few key machine learning techniques, such as supervised methods for machine learning (regression and classification), which attempt to map data onto desired outputs, and unsupervised methods (clustering and association), which attempt to find structure within data itself; use openly available tools to implement these techniques on text and image data; learn how to assess the effectiveness of different techniques on particular datasets; and discuss basic issues that confront all machine learning methods. 

Readings, class discussions, and hands-on sessions will be complemented by guest lectures (TBD) from machine learning practitioners. Students will be assessed via a final project developed throughout the course, in addition to the project proposal, presentation, class participation, and lab assignments.

This syllabus is a living document; expect it to evolve over the course of the semester. All changes will be communicated in class and the updated syllabus will be uploaded on LMS. Since this is a new course, your participation and input will be crucial in shaping it to your needs. Feel free to ask questions and give feedback or suggestions, in person or via email, as we move into the semester.

### Course Schedule:

|  Week   | Session                                                                | Lab                                                                        | Assignment       | Guest                  |
|---------|------------------------------------------------------------------------|----------------------------------------------------------------------------|------------------|------------------------|
| 1  | Introduction – What is Machine Learning?                               | Getting started with Python, Git                                           | -                | -                      |
| 2  | Data, Bias, Communication                                              | Working with data in Python, Visualization                                 | #1 TBD           | Kaizer Fung            |
| 3  | Intro to Supervised Learning - Linear Models                           | Supervised learning in Python with scikit-learn                            | -                | -                      |
| 4  | Supervised Learning cont. - Trees, Forests, Ensembles                  | Supervised learning in Python with scikit-learn                            | #2 TBD           | -                      |
| 5  | Unsupervised learning - Clustering, Dimensionality Reduction           | Unsupervised learning in Python with scikit-learn                          | -                | -                      |
| 6  | Project planning                                                       | Project Workshop                                                           | Project Proposal | TBD                    |
| 7  | NO CLASS - Midterm break                                               | -                                                                          | -                | -                      |
| 8  | Model Pipelines: Evaluation, Tuning, Feature Processing                | End to End ML pipeline                                                     | #3 TBD           | -                      |
| 9  | Neural Networks                                                        | Neural Network with PyTorch [TBD], Sequential models                       | -                | -                      |
| 10 | Neural Networks - cont.                                                | Neural Network with PyTorch [TBD], Advanced models: Convolution, Recurrent | #4 TBD           | -                      |
| 11 | ML Ecosystem - Cloud, MLOps, Production, Pre-Trained Models, APIs      | Cloud infrastructure (AWS) [TBD], Working with APIs                        | -                | TBD                    |
| 12 | Human-Centric AI, Fairness                                             | TBD                                                                        | -                | TBD                    |
| 13 | Labor and Machine Learning                                             | TBD                                                                        | -                | Elizabeth Anne Watkins |
| 14 | Be a Good Engineer! Software Abstraction, Reproducibility, Open Source | TBD                                                                        | -                | TBD                    |
| 15 | Industry and Career                                                    | TBD                                                                        | -                | TBD                    |
| 16 | Presentations                                                          | -                                                                          | -                | TBD                    |


#### Week 1: Introduction – What is Machine Learning?
**Readings:**
* Noah Lorang (2016) [Data scientists mostly just do arithmetic and that’s a good thing](https://m.signalvnoise.com/data-scientists-mostly-just-do-arithmetic-and-thats-a-good-thing/)t.
* David Donoho (2017) [50 Years of Data Science](https://www.tandfonline.com/doi/full/10.1080/10618600.2017.1384734), Journal of Computational and Graphical Statistics, 26:4, 745-766.
* Meredith Broussard, Artificial Unintelligence, ch.2-3 (13-39)
* Gideon Lewis-Kraus (2016) [“The Great A.I. Awakening”](https://www.nytimes.com/2016/12/14/magazine/the-great-ai-awakening.html)


#### Week 2: Data, Bias, Communication
**Readings:**
* Paul Ford (2015) [“What is Code?”](https://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/)
* Lisa Gitelman (ed.) (2013) [“Raw Data” Is an Oxymoron".](hhttp://raley.english.ucsb.edu/wp-content/Engl800/RawData-excerpts.pdf) introduction (1-14)
* Andrey Kurenkov (2020) [Lessons from the pulse model](https://thegradient.pub/pulse-lessons/)
* Wickham, H. (2014). [Tidy Data. Journal of Statistical Software](https://www.jstatsoft.org/article/view/v059i10), 59(10), pp 1 - 23. 
* Karen Hao (2019) [This is how AI bias really happens—and why it’s so hard to fix](https://www.technologyreview.com/2019/02/04/137602/this-is-how-ai-bias-really-happensand-why-its-so-hard-to-fix/)
* O'Neil, C. (2016). [The Ethical Data Scientist](https://slate.com/technology/2016/02/how-to-bring-better-ethics-to-data-science.html)
* Chun, W. H. K. (2005). O[n software, or the persistence of visual knowledge](https://www.academia.edu/779925/On_software_or_the_persistence_of_visual_knowledge). grey room, 26-51.

**Supplemental Material:**
* Konold, C., Finzer, W., & Kreetong, K. (2017). [Modeling as a Core Component of Structuring Data. Statistics Education Research Journal](https://iase-web.org/documents/SERJ/SERJ16(2)_Konold.pdf), 16(2). 
* [Wrongfully Accused by an Algorithm](https://www.nytimes.com/2020/08/03/podcasts/the-daily/algorithmic-justice-racism.html)
* Prabhu, V. U., & Birhane, A. (2020). [Large image datasets: A pyrrhic win for computer vision?](https://arxiv.org/pdf/2006.16923)
* Galloway, A. (2015). [“The Computational Decision”](http://cultureandcommunication.org/galloway/the-computational-decision)
* Wong, D. M. (2010). The Wall Street Journal guide to information graphics: The dos and don'ts of presenting data, facts, and figures. WW Norton.


### Course Goals:

The goals of this course are to:

* Introduce students to key concepts and some common techniques in machine learning, as well as openly available tools 
* Help students to develop technical and critical thinking skills regarding machine learning 
* Enable students to conduct a machine learning experiment and communicate the result of their project

### Student Learning Outcomes:

By the end of the course, students will be able to:

* Describe different machine learning methods, including their limitations
* Select an appropriate machine learning method for a given use case
* Implement machine learning algorithms and assess their performance
* Execute a machine learning experiment using openly available tools
* Support the design of their experiment by discussing both the technical aspect and the topic’s significance

### Textbooks, Readings and Materials:
All reading materials and course slides (if applicable) will be provided as hyperlinks or downloadable files through LMS.

Students will need a Google account for certain lab sessions. I believe the Pratt email address can serve this purpose, giving you access to Google Drive and Colab. In the latter part of the course, students will also need an account for Runway ML; details on how to sign up will be provided as needed.

Additional resources including technical tutorials, example projects and datasets, resources about critical discourse, and more are listed on this webpage, and will be updated as necessary

### Revisions to the Syllabus

All changes will be communicated in class and the updated syllabus will be uploaded on LMS. This version is current as of August 26, 2019 September 11, 2019.
