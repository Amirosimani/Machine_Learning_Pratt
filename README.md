<img src="./img/Pratt_logo.png"
     alt="Pratt logo"
     style="float: left; margin-right: 10px;" />

# Machine Learning Course
**INFO 656-01 - Fall 2020/2023**

- [Course Description](#course-description)
- [Course Schedule](#course-schedule)
- [Textbooks and Readings Materials](#textbooks-and-readings-materials)
- [Readings and Discussions](#readings-and-discussions)
  * [Week 1: Introduction – What is Machine Learning?](#week-1--introduction---what-is-machine-learning-)
  + [Week 2: Data, Bias, Communication](#week-2--data--bias--communication)
  + [Week 3: Intro to Supervised Learning - Linear Models](#week-3--intro-to-supervised-learning---linear-models)
  + [Week 4: Supervised Learning  cont. - Trees, Forests, Ensembles](#week-4--supervised-learning--cont---trees--forests--ensembles)
  + [Week 5: Unsupervised learning - Clustering, Dimensionality Reduction](#week-5--unsupervised-learning---clustering--dimensionality-reduction)
  + [Week 6: Model Pipelines: Evaluation, Tuning, Feature Processing](#week-6--model-pipelines--evaluation--tuning--feature-processing)
  + [Week 7: NO CLASS - Midterm break](#week-7--no-class---midterm-break)
  + [Week 8: Project planning](#week-8--project-planning)
  + [Week 9: Neural networks](#week-9--neural-networks)
  + [Week 10: Neural Networks - cont.](#week-10--neural-networks---cont)
  + [Week 11: Week 11: ML Ecosystem - Cloud, Open-Source, APIs](#week-11--ml-ecosystem---cloud--mlops--production--pre-trained-models--apis)
  + [Week 12: Week 12: GenAI - Prompt Engineering](#week-12--human-centric-ai--fairness)
  + [Week 13: Week 13: Human-Centric AI: discussing Labor and Fairness in machine learning](#week-13--labor-and-machine-learning)
  + [Week 14: Be a Good Engineer! Software Abstraction, Reproducibility, MLOps, Production](#week-14--be-a-good-engineer--software-abstraction--reproducibility--open-source)
  + [Week 15: Industry and Career](#week-15--industry-and-career)
  + [Week 16: Presentations](#week-16--presentations)
  + [Revisions to the Syllabus](#revisions-to-the-syllabus)
* [Lab assignments](#lab-assignments)
* [Project proposal](#project-proposal)
* [Final project + presentation](#final-project---presentation)
* [Course Goal](#course-goal)
* [Student Learning Outcomes](#student-learning-outcomes)
* [Assessment and Grading](#assessment-and-grading)
* [Portfolio](#portfolio)
* [Policies](#policies)

## Course Description

Machine learning is a rapidly growing field that develops algorithms for tasks such as data classification and prediction. These algorithms are programmed to operate and adjust themselves independently of human intervention (i.e., to learn), allowing data work to occur quickly and at scale. Machine learning is a key technology behind the automation across many social areas today, often branded AI.

This course offers an introduction to machine learning as a practical tool that we can use, and as a technological field with social implications. We will learn about key concepts in machine learning; survey a few key machine learning techniques, such as supervised methods for machine learning (regression and classification), which attempt to map data onto desired outputs, and unsupervised methods (clustering and association), which attempt to find structure within data itself; use openly available tools to implement these techniques on text and image data; learn how to assess the effectiveness of different techniques on particular datasets; and discuss basic issues that confront all machine learning methods. 

Readings, class discussions, and hands-on sessions will be complemented by guest lecturers (TBD) from machine learning practitioners. Students will be assessed via a final project developed throughout the course, in addition to the project proposal, presentation, class participation, and lab assignments.

This syllabus is a living document; expect it to evolve over the course of the semester. All changes will be communicated in class and the updated syllabus will be uploaded on LMS. Since this is a new course, your participation and input will be crucial in shaping it to your needs. Feel free to ask questions and give feedback or suggestions, in person or via email, as we move into the semester.


## Course Schedule

| Week | Session                                                                | Lab       | Assignment       |
|------|------------------------------------------------------------------------|-----------|------------------|
| 1    | Introduction – What is Machine Learning?                               | Getting started with Python, Git   | - |
| 2    | Data, Bias, Communication          | Working with data in Python, Visualization    | #1 Exploratroy Data Analysis |
| 3    | Intro to Supervised Learning - Linear Models | Supervised learning in Python with scikit-learn  | -       |
| 4    | Supervised Learning cont. - Trees, Forests, Ensembles | Supervised learning in Python with scikit-learn   |    |
| 5    | Unsupervised learning - Clustering, Dimensionality Reduction   | Unsupervised learning in Python with scikit-learn | #2 Surpvised Model  |
| 6   | Model Pipelines: Evaluation, Tuning, Feature Processing | End to End ML pipeline      |      |
| 7    | NO CLASS - Midterm break                                               | -      | -     |
| 8    | Project planning       | Project Workshop        | Project Proposal |
| 9    | Neural Networks      | Neural Network, Sequential models         | -     |
| 10   | Neural Networks - cont.       | Neural Network, Advanced models: Convolution |  #3 Neural Networks   |
| 11   | ML Ecosystem - Cloud, Open-Source, Pre-Trained Models, APIs | Working with APIs | - |
| 12   | Human-Centric AI, Fairness   | TBD    | -  |
| 13   | Labor and Machine Learning   | TBD         | -      |
| 14   | Be a Good Engineer! Software Abstraction, Reproducibility, MLOps, Production | TBD   | -     |
| 15   | Industry and Career       | TBD        | -|
| 16   | Presentations     | -     | -          |



## Textbooks and Readings Materials
Throughout the semester, we will survey diverse perspectives about machine learning as a socially situated technology. The assigned readings will be complemented by in-class discussions, typically at the beginning of the class.

Throughout the semester, we will use the following books frequently:

> * James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). An introduction to statistical learning
> * Müller, A. C., & Guido, S. (2016). Introduction to machine learning with Python: a guide for data scientists.".
> * Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep learning. MIT press.


All reading materials and course slides (if applicable) will be provided as hyperlinks or downloadable files through Canvas.

Students will need a Google/AWS account for certain lab sessions. I believe the Pratt email address can serve this purpose, giving you access to Google Drive and Colab. Details on how to sign up will be provided as needed.

Additional resources including technical tutorials, example projects and datasets, resources about critical discourse, and more are listed on this GitHub repo, and will be updated as necessary: https://github.com/Amirosimani/Machine_Learning_Pratt

## Readings and Discussions
A provocation will include a summary of key points in the readings, as well as questions / observations you would like to raise or make. The provocations will serve as starting points of the in-class discussion and some of them will scaffold towards the project proposal and final project.

Students who are not motivators for the week are expected to complete the readings before class, and contribute to the discussion in class and/or online by replying to the forum thread.


### Week 1: Introduction – What is Machine Learning?

* Noah Lorang (2016) [Data scientists mostly just do arithmetic and that’s a good thing](https://m.signalvnoise.com/data-scientists-mostly-just-do-arithmetic-and-thats-a-good-thing/).
* David Donoho (2017) [50 Years of Data Science](https://www.tandfonline.com/doi/full/10.1080/10618600.2017.1384734), Journal of Computational and Graphical Statistics, 26:4, 745-766.
* Paul Ford (2015) [“What is Code?”](https://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/)


### Week 2: Data, Bias, Communication

* Wickham, H. (2014). [Tidy Data. Journal of Statistical Software](https://www.jstatsoft.org/article/view/v059i10), 59(10), pp 1 - 23. 
* Lisa Gitelman (ed.) (2013) [“Raw Data” Is an Oxymoron".](http://raley.english.ucsb.edu/wp-content/Engl800/RawData-excerpts.pdf) introduction (1-14)
* Karen Hao (2019) [This is how AI bias really happens—and why it’s so hard to fix](https://www.technologyreview.com/2019/02/04/137602/this-is-how-ai-bias-really-happensand-why-its-so-hard-to-fix/)


**Supplemental Material:**
* Chun, W. H. K. (2005). O[n software, or the persistence of visual knowledge](https://www.academia.edu/779925/On_software_or_the_persistence_of_visual_knowledge). grey room, 26-51.
* Galloway, A. (2015). [“The Computational Decision”](http://cultureandcommunication.org/galloway/the-computational-decision)
* [Wrongfully Accused by an Algorithm](https://www.nytimes.com/2020/08/03/podcasts/the-daily/algorithmic-justice-racism.html)



### Week 3: Intro to Supervised Learning - Linear Models

* Stephanie Yee and Tony Chu, [“A visual introduction to machine learning”](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/ )
* Daly, L. (2017) [“AI Literacy: The basics of machine learning”](https://worldwritable.com/ai-literacy-the-basics-of-machine-learning-2e20f93e34b4)
* Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep learning. MIT press. Chapter 5.1 (96-105)


**Supplemental Material:**
* Khan Academy, “[Least-squares regression equations”](https://www.khanacademy.org/math/statistics-probability/describing-relationships-quantitative-data/regression-library/v/introduction-to-residuals-and-least-squares-regression) (MOOC module, playlist) 
* Gene Kogan and Francis Tseng, [“Fundamentals, introduction to machine learning”](https://github.com/ml4a/ml4a-guides/blob/master/notebooks/fundamentals.ipynb )
* James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). An introduction to statistical learning (Vol. 112, p. 18). Chapter 2.1 (15-28)



### Week 4: Supervised Learning  cont. - Trees, Forests, Ensembles

* James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). An introduction to statistical learning (Vol. 112, p. 18). Chapter 8 (303-332)
* Müller, A. C., & Guido, S. (2016). Introduction to machine learning with Python: a guide for data scientists.". Chapter 2.3 (31-121)


**Supplemental Material:**
* Chris Deotte, [“Classifier Playground”](http://www.ccom.ucsd.edu/~cdeotte/programs/classify.html)


### Week 5: Unsupervised learning - Clustering, Dimensionality Reduction

* James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). An introduction to statistical learning (Vol. 112, p. 18). Chapter 10 (373-412)
* Müller, A. C., & Guido, S. (2016). Introduction to machine learning with Python: a guide for data scientists.". Chapter 3 (133-210)


**Supplemental Material:**
* Elish, M.C. & Hwang T., [An AI Pattern Language](https://datasociety.net/pubs/ia/AI_Pattern_Language.pdf). Chapter 2 (16-33)

### Week 6: Model Pipelines: Evaluation, Tuning, Feature Processing

* James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). An introduction to statistical learning (Vol. 112, p. 18). Chapter 2.2 (28-42)
* Müller, A. C., & Guido, S. (2016). Introduction to machine learning with Python: a guide for data scientists.". Chapter 5 (253-304)

### Week 7: NO CLASS - Midterm break


### Week 8: Project planning

* Patrick Hebron, [“Rethinking Design Tools in the Age of Machine Learning”](https://medium.com/artists-and-machine-intelligence/rethinking-design-tools-in-the-age-of-machine-learning-369f3f07ab6c)
* Lovejoy, J. & Holbrook, J. (2017). [Human-Centered Machine Learning](https://medium.com/google-design/human-centered-machine-learning-a770d10562cd)
* Kearns, M., & Roth, A. (2019). The ethical algorithm: The science of socially aware algorithm design. Oxford University Press., chapter 1

**Supplemental Material:**
* Example projects and resources: https://www.are.na/achim-koh/ml-design-ish (The linked list is a preliminary one and will be updated; also, the examples are meant primarily as inspirations, and do not indicate what the final project should look like)


### Week 9: Neural networks

* 3Blue1Brown, “[Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)” (YouTube playlist) 
* Müller, A. C., & Guido, S. (2016). Introduction to machine learning with Python: a guide for data scientists.". Chapter 2.3.8 (106-121)
* Chris Deotte, [“Neural Network Playground”](http://www.ccom.ucsd.edu/~cdeotte/programs/neuralnetwork.html)


**Supplemental Material:**
* The Coding Train, “[Neural Networks - The Nature of Code”](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6aCibgK1PTWWu9by6XFdCfh) (YouTube playlist)
* Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep learning. MIT press. Chapter 6

### Week 10: Neural Networks - cont.
* Daniel Smilkov and Shan Carter, [“A Neural Network Playground”](https://playground.tensorflow.org/)
* Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep learning. MIT press. Chapter 9
* Andrew Ng. [Nuts and Bolts of Applying Deep Learning](https://www.youtube.com/watch?v=F1ka6a13S9I)

**Supplemental Material:**
* Daniel Shiffman, ["The Nature of Code"](https://natureofcode.com/book/chapter-10-neural-networks/), ch.10 

### Week 11: ML Ecosystem - Cloud, Open-Source, APIs
* [Machine learning in the cloud is helping businesses innovate](https://www.technologyreview.com/2021/10/15/1037291/machine-learning-in-the-cloud-is-helping-businesses-innovate/)
* [Why Is Open-Source So Important? Part One: Principles And Parity](https://www.forbes.com/sites/charlestowersclark/2019/09/24/why-is-open-source-so-important-part-one-principles-and-parity/#5882840961f7)
* Andrew Ng. [Transfer Learning](https://www.youtube.com/watch?v=yofjFQddwHE)


**Supplemental Material:**
* Podcast: [Jitendra Malik: Computer Vision](https://lexfridman.com/jitendra-malik/)
* Podcast: [Data Science in the Cloud](https://www.datacamp.com/community/podcast/data-science-in-the-cloud) (with Paige Bailey). 

### Week 12: GenAI - Prompt Engineering


### Week 13: Human-Centric AI: discussing Labor and Fairness in machine learning

* Anette Zimmermann, Elena di Rosa, Hochan Kim, [Technology Can't Fix Algorithmic Injustice](http://bostonreview.net/science-nature-politics/annette-zimmermann-elena-di-rosa-hochan-kim-technology-cant-fix-algorithmic)
* Alex Galloway, [“Are Algorithms Biased?”](http://cultureandcommunication.org/galloway/are-algorithms-biased)
* [is your algorithm racist?](https://www.politico.com/agenda/story/2018/02/07/algorithmic-bias-software-recommendations-000631/)
* Kate Crawford and Vladan Joler, [Anatomy of an AI System](https://anatomyof.ai/)
* Cade Metz, [“A.I. Is Learning From Humans. Many Humans.”](https://www.nytimes.com/2019/08/16/technology/ai-humans.html)
* [Algorithmic Management in the workplace](https://datasociety.net/wp-content/uploads/2019/02/DS_Algorithmic_Management_Explainer.pdf)
* [Sepsis Watch in Practice.](https://points.datasociety.net/sepsis-watch-in-practice-5b06f88655fe)


**Supplemental Material:**
* West, S.M., Whittaker, M. and Crawford, K. (2019). [Discriminating Systems: Gender, Race and Power in AI. AI Now Institute](https://ainowinstitute.org/discriminatingsystems.pdf)
* Julia Angwin et al., [“Machine Bias”](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)
* Diana ben-Aaron, [“Weizenbaum examines computers and society”](http://tech.mit.edu/V105/N16/weisen.16n.html)
* Podcast: [Peter Wang (part 1/2): CEO/founder Anaconda, Creator of PyData](https://podcasts.apple.com/us/podcast/peter-wang-part-1-2-ceo-founder-anaconda-creator-of-pydata/id1478016790?i=1000459268650)
* Nicolas Papernot, N., & Goodfellow, I. (2018) [Privacy and ML, two unexpected allies](http://www.cleverhans.io/privacy/2018/04/29/privacy-and-machine-learning.html)
* Cathy O'Neil. Weapons of Math Destruction: How Big Data Increases Inequality and Threatens Democracy. Broadway Books. Conclusion (199-218)
* Siddhartha Mukherjee, [“AI Versus MD”](http://web.archive.org/web/20170427141526/http://www.newyorker.com/magazine/2017/04/03/ai-versus-md) 
* [where will predictive text take us?](https://www.newyorker.com/magazine/2019/10/14/can-a-machine-learn-to-write-for-the-new-yorker)
* [How three French students used borrowed code to put the first AI portrait in Christie’s](https://www.theverge.com/2018/10/23/18013190/ai-art-portrait-auction-christies-belamy-obvious-robbie-barrat-gans)
* Astra Taylor, [“The Automation Charade”](https://logicmag.io/failure/the-automation-charade/)
* Rosenblat, A. (2018). Uberland: How algorithms are rewriting the rules of work. Univ of California Press.


### Week 14: Be a Good Engineer! Software Abstraction, Reproducibility, MLOps, Production
* Greg Wilson, Jennifer Bryan, Karen Cranston, Justin Kitzes, Lex Nederbragt, Tracy K. Teal (2017). [Good enough practices in scientific computing](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510)
* Causey, Tray. [Software development skills for data scientists](http://treycausey.com/software_dev_skills.html)
* [Production ML systems](https://developers.google.com/machine-learning/crash-course/production-ml-systems)


**Supplemental Material:**
* [MLOps](https://cloud.google.com/solutions/machine-learning/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning)
* Justin Kitzes, Daniel Turek, Fatma Deniz (2018). [The Practice of Reproducible Research](https://www.practicereproducibleresearch.org)
* Cooper, Z. (2020) [Getting started with contributing to open source](https://stackoverflow.blog/2020/08/03/getting-started-with-contributing-to-open-source/?utm_source=Iterable&utm_medium=email&utm_campaign=the_overflow_newsletter)
* [Docker for Data Science](https://www.kdnuggets.com/2018/01/docker-data-science.html)


### Week 15: Industry and Career
* [Market your data science like a product](https://medium.com/indeed-engineering/marketing-for-data-science-a-7-step-go-to-market-plan-for-your-next-data-product-60c034c34d55)
* Caitlin Hudon (2018). [Imposter syndrome in data science](https://caitlinhudon.com/2018/01/19/imposter-syndrome-in-data-science/)
* [What Data Scientists Really Do, According to 35 Data Scientists](https://hbr.org/2018/08/what-data-scientists-really-do-according-to-35-data-scientists)

**Supplemental Material:**
* Podcast: [Getting Your First Data Science Job](https://www.datacamp.com/community/podcast/getting-your-first-data-science-job) (with Chris Albon). 
* Shana Lynch, “[Andrew Ng: Why AI Is the New Electricity”](https://www.gsb.stanford.edu/insights/andrew-ng-why-ai-new-electricity)
* [Doing data science at Twitter](https://medium.com/@rchang/my-two-year-journey-as-a-data-scientist-at-twitter-f0c13298aee6)


### Week 16: Presentations

### Revisions to the Syllabus

All changes will be communicated in class and the updated syllabus will be uploaded on Canvas. This version is current as of August 14, 2023.

-----
## Lab assignments
The latter part of each class will be a lab session related to the topic of the week. Sometimes, the lab session will be accompanied by a lecture-style session before it; in other cases, we will move into the lab session right after discussions.

At the end of some lab sessions, I will give you take-home assignments (4 total). The assignments will scaffold towards the final project. For example, you will be asked to explain some machine learning terminology or write code that does a specific task. 

You need to submit your coding assignments through our dedicated GitHub Classroom. Details on how to submit the homework will be communicated in class. The homework assignments are due by the end of the day Monday before the next class.

I may also ask you to write down the amount of time you spent working on the assignment. This amount of time does NOT affect gradings in any way; I am asking in order to gauge whether I am giving you too much work or whether you are having trouble with some of the course material.

---

## Project proposal
I will ask you to choose a topic that you would like to explore in your final project and to submit a proposal by mid-semester.

On week 6, we will have an in-class activity where you will share your idea(s) and give peer feedback. Your 800- to 1200-word proposal is due by the end of the following, and should include:
•   A description of the data you intend to use
•   A description of the machine learning task you intend to perform
•   A tentative and brief survey of existing work on the topic
•   A discussion of the significance of your topic

We will discuss the proposal in further detail in the coming weeks.

---

## Final project + presentation
Your final project is to run an experiment that applies a machine learning technique (such as classification, regression, clustering, etc.) that we learned on a dataset of your choice. You can design the project as a complete piece on its own, or as a component of a larger project. 

Projects are due before the final class in the form of a write-up detailing your work process; you also need to submit the resulting model /  dataset and code used. We will dedicate our final class to presentations.

A detailed rubric for the project and presentation will be distributed separately.

---


## Course Goal

The goals of this course are to:

* Introduce students to key concepts and some common techniques in machine learning, as well as openly available tools 
* Help students to develop technical and critical thinking skills regarding machine learning 
* Enable students to conduct a machine learning experiment and communicate the result of their project

---
## Student Learning Outcomes

By the end of the course, students will be able to:

* Describe different machine learning methods, including their limitations
* Select an appropriate machine learning method for a given use case
* Implement machine learning algorithms and assess their performance
* Execute a machine learning experiment using openly available tools
* Support the design of their experiment by discussing both the technical aspect and the topic’s significance

---
## Assessment and Grading

```
Lab assignments 20%
Participation (discussions and peer feedback) 30%
Project proposal 10%
Final project 30%
Presentation 10%
```

Pratt’s grading scale:  

| A  | Superior work           | 4.0 | 96-100 |
|----|-------------------------|-----|--------|
| A- | Superior work           | 3.7 | 90-95  |
| B+ | Very good work          | 3.3 | 87-89  |
| B  | Very good work          | 3.0 | 83-86  |
| B- | Very good work          | 2.7 | 80-82  |
| C+ | Marginally satisfactory | 2.3 | 77-79  |
| C  | Marginally satisfactory | 2.0 | 73-76  |
| F  | Failed:                 | 0.0 | 0-72   |

---
## Portfolio

Work completed for this course may be included in your portfolio. For more information on each program’s portfolio requirements, please visit the program’s respective webpage:

* MS Library & Information Science: Portfolio - http://bit.ly/prattmslisportfolio
* MS Information Experience Design: Portfolio - http://bit.ly/prattmsixdportfolio
* MS Data Analytics and Visualization: Portfolio - http://bit.ly/prattmsdavportfolio 
* MS Museums and Digital Culture: Portfolio - http://bit.ly/prattmsmdcportfolio 
You are encouraged to meet with your advisor about including projects in your portfolio. 

---
## Policies

This Course’s Attendance Policy

Students are allowed two individual absences for any reason; no notice or documentation is required. If you miss a session, be sure that you complete the readings, consult your classmates or the professor about the class, and (as always) demonstrate your knowledge of previous topics in later sessions. Upon a third or fourth absence, your grade will be lowered by one mark for each absence. Five absences will result in failure of the course (F). Also, please note that a grade of C- is considered failing at the graduate level.

Students who encounter long-term health issues should provide documentation to the Office of Health and Counseling and discuss their options with the professor.

| Absences | Penalty                 | Example                                                                         |
|----------|-------------------------|---------------------------------------------------------------------------------|
| 0-2      | None                    | NA                                                                              |
| 3-4      | One mark per absence    | A → A- (3rd absence) → B+ (4th absence)<br> A- → B+ (3rd absence) → B (4th absence) <br>|
| 5+       | Failure of the course   | NA                                                                              |


For more information on Pratt Institute’s Attendance Policy, please visit http://bit.ly/prattattendance.  

Academic Integrity Code

Academic integrity at Pratt means using your own and original ideas in creating academic work. It also means that if you use the ideas or influence of others in your work, you must acknowledge them. For more information on Pratt’s Academic Integrity Standards, please visit http://bit.ly/prattacademicintegrity. 

Students with Disabilities and Accessibility

Pratt Institute is committed to the full inclusion of all students. If you are a student with a disability and require accommodations, please contact the Learning/Access Center (L/AC) at LAC@pratt.edu to schedule an appointment to discuss these accommodations. Students with disabilities who have already registered with the L/AC are encouraged to speak to the professor about accommodations they may need to produce an accessible learning environment. 

Requests for accommodation should be made as far in advance as reasonably possible to allow sufficient time to make any necessary modifications to ensure the relevant classes, programs, or activities are readily accessible. The Learning/Access Center is available to Pratt students, confidentially, with additional resources and information to facilitate full access to all campus programs and activities and provide support related to any other disability-related matters.

For more information, please visit http://www.pratt.edu/accessibility/.

Human Rights, Equity, BERT, and Title IX

Pratt Institute seeks to provide an environment that is free of bias, discrimination, and harassment.  If you have been the victim of harassment, discrimination, bias, or sexual misconduct, we encourage you to report this.  

If you inform me (your professor) of an issue of harassment, discrimination or bias, or sexual misconduct I will keep the information as private as I can, but I am required to bring it to the attention of the institution’s Title IX Coordinator. You can access Title IX services by emailing titleix@pratt.edu. You can also speak to someone confidentially by contacting our non-mandatory reporters: Health Services at 718-399-4542, Counseling Services 718-687-5356 or Campus Ministries 718-596-4840. 

In cases of Bias, this information may go to our Bias Education & Response Taskforce (BERT). You can contact BERT by either reaching out directly via bert@pratt.edu or by contacting the BERT Co-Chair and Title IX Coordinator, Dr. Esmilda Abreu. 
 
For more information, please refer to the Community Standards webpage: http://bit.ly/prattcommunitystandards. 

