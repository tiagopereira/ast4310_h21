# Projects

## Overview

There are a total of five projects, to be handed in at different times and with a different weight on the final grade, as listed below.

|        | Deadline          | Weight  |  Topic  |
| ------------- |:-------------:| :----:|:---|
| [Project 1](https://github.com/tiagopereira/ast4310/tree/main/notebooks/project1)     | 16 Sep  | 10% | Basic spectral line formation |
| [Project 2](https://github.com/tiagopereira/ast4310/tree/main/notebooks/project2)     | 07 Oct  | 15% | Line strengths and curve of growth |
| [Project 3](https://github.com/tiagopereira/ast4310/tree/main/notebooks/project3)     | 28 Oct  | 25% | *La Palma* |
| [Project 4](https://github.com/tiagopereira/ast4310/tree/main/notebooks/project4)     | 18 Nov  | 25% | Solar continua and LTE line formation |
| Project 5     | 09 Dec  | 25% | *Different options:* |
| <ul><li><a href="https://github.com/tiagopereira/ast4310/tree/main/notebooks/project5a">Project 5a</a></li></ul>    | | | <ul><li>3D Radiative Transfer</li></ul>|
| <ul><li><a href="https://github.com/tiagopereira/ast4310/tree/main/notebooks/project5b">Project 5b</a></li></ul>   | | | <ul><li>Scattering</li></ul> |
| <ul><li><a href="https://github.com/tiagopereira/ast4310/tree/main/notebooks/project5c">Project 5c</a></li></ul>   | | | <ul><li>Polarised Radiative Transfer</li></ul> |

For project 5 there are three different options to chose from (each person/group can only select one). 


## Repository

The project descriptions and questions are given in Jupyter notebook format, and can be found at the [course's github repository](https://github.com/tiagopereira/ast4310). They will be available and up-to-date on JupyterHub, so you can easily visualise them by browsing on Jupyter. You can also check them out on github, but sometimes they display poorly. 

Most of the time you should be using Jupyter lab, a more modern and complete version of Jupyter notebook. In some cases the LaTeX parts in Markdown may not render. You can try waiting a bit, or re-running (Ctrl+Enter) the problematic markdown cells. In some cases, making a small change (e.g. adding a space) and re-running the cell fixes the problem.

## Format and delivery

The projects should be handed in as Jupyter notebooks (in Python). The expected workflow is that you work on your notebooks on JupyterHub, and when done download them from JupyterHub (right click on the file then download, when you are on Jupyter lab).

Please have a look at the [Guidelines notebook](https://github.com/tiagopereira/ast4310/blob/main/notebooks/Guidelines.ipynb) (under `ast4310/notebooks`) for more details on what is expected in the notebooks. There is also a [Template notebook](https://github.com/tiagopereira/ast4310/blob/main/notebooks/template.ipynb) that you can copy and use as a starting point for your assignments. The project deliveries will be assessed anonymously, but please remember to include your candidate numbers in the notebook submitted.

The assignments will be handed using [Devilry](https://devilry.ifi.uio.no).  The projects should be handed in groups of two. In exceptional cases, they can be handed individually or in groups of three.

!!! info
    Groups are not enabled in Devilry. This means that students in a group will need to submit the same files on Devilry. This is because peer review is individual (see below), therefore group members will not necessarily have the same final grade for a project.

In addition to the notebook file, you should upload also all necessary files to run or notebook, or additional files you created along your notebook (e.g. a data file with the results of a long calculation). *You do not need to upload the additional files that were present in the repository* (e.g. atom files, images, etc.). Loading data files or code from the internet is not allowed.

## Grading

The project weights are specified in the table at the top of this page. Each project will have a numerical grade between 0 and 100, and the final grade is the weighed sum of all project grades, rounded to the closest integer. The final numerical grade will be converted to the A-F scale according to the usual scale:

| Points | Grade |
|:-------:|:-----|
| 92 - 100 |  A |
| 77 - 91 |  B |
| 58 - 76  | C |
| 46 - 57 |  D |
| 40 - 45 |  E |
| 0 - 39 |  F |

For the 100 points assigned to each project, 95 points are for the report itself (Jupyter notebook), and 5 points are given for peer review. The grade of each project can be improved by submitting an improved version (**up to 30% of points not earned**), see below for details. 

### Peer review

To mimic the peer-review process in scientific publications, you will have the opportunity to review the work of your colleagues. The main goal of peer review is to give constructive feedback so that your colleagues can learn from their mistakes and improve the submission. **Peer review is optional.** It will give up to 5 points that will be added to your project grade. If you have a perfect score in the project but elect not to do peer review, you will get a grade of 95. 

Peer review will be double-blind and individual. Each element of a group will be given a different assignment to review. It is expected that the 5 points will be awarded for most peer reviews, although obviously low-quality peer reviews will receive zero points. Borderline cases may be given less than 5 points. Examples of a low-quality review are:

* Few comments on the work
* Mostly meaningless or off-the-mark comments, where it is obvious the reviewer did not properly read the work
* Contains offensive or inappropriate comments

Examples of meaningless comments are: *Nice work!*, *You did a good plot here!*, *Very good!*. These may be encouraging, but they don't provide any feedback to your colleagues. It's fine to give positive feedback, but please be specific, e.g.: *This part was easy to read, I enjoyed how you linked your findings to the lecture materials.*, *This is a nice plot because the two cases are clearly distinguishable, and the lines/marking are easy to see.*

#### Peer review for the *reviewer*

* After the projects are handed in in Devilry, we will work quickly to assign you a project to review. A Jupyter notebook will be sent to you on Devilry. The project deadlines are on Fridays; you should expect to receive your assignment on the following Monday.

* The deadline to submit peer review is one week after the original submission deadline (ie, Friday to Friday).

* Write your review in the notebook you receive, by adding additional markdown cells, enclosing your comments with an HTML box of the following kind (please do not change the colour of the `div` box):

```html
<div style="background-color:#e6e6e6; padding:10px; border-style:
solid;; border-color:#0d0d0d; border-width:1px">

Your markdown comments here.

* Can also use
* a bulleted list,

Other markdown, LaTeX: $\epsilon$, etc.

</div>
```

* Your job as a reviewer is to find out if each question is adequately answered, for example by answering the following questions:
    * Are the assumptions correct, and well spelled out?
    * Are the computations adequate to the job, and the code easy to read?
    * Are there any major flaws in the answer(s)?
    * Is the text well-written and concise?
    * Are plots well laid out?
* You don't need to answer all of the above, or go exhaustively through the calculations or the code. The point is more to look at the big picture.
* It is not the job of the reviewer to spell check or correct the language (in scientific publications, this is the job of the editor and/or language editor). If you find there are too many language errors, you can mention it as a general comment, e.g.: *This work would benefit from some proofreading, there are several typos and grammatical errors.*
* It is not the job of the reviewer to force her/his view into the writing of the answers, but provide a neutral viewpoint. 
* Do not be afraid to point out mistakes if you find them, but always try to do so in a constructive manner and criticise the work, not the person. Write your feedback as you would like to receive it.
* Avoid discussing your peer review assignments with your colleagues. 
* The only exception of the above is sharing with your group colleague if you happen to find an answer that is markedly better than your own. This is also a learning experience for you, and in such cases you are encouraged to use what you've learned from other projects when submitting a revised version (see below).
* If you are using parts of someone else's project in your revised submission, **always give credit**. E.g. *we changed X and Y based on an approach learned from another project we reviewed*. In these cases, try to modify your own answer as opposed to copying someone else's answer or source code. **Wholesale copying of other answers will be considered cheating.**




#### Peer review for the *authors*

* About one week after the original submission deadline, you will receive feedback from the teachers plus any feedback from peer review
* Comments you receive from peer review will not affect your grade, only the assessment by the teachers.
* Do not take the comments from peer review at face value. It is possible that the reviewer is wrong.
* Do not take any negative comments personally. The reviewer is commenting on the work that you submitted, not on you as a person.
* Avoid discussing the comments from peer review outside your group, and especially do not confront other students or suggest she/he was the referee.


### Submitting an improved version

A way to get bonus points is to submit an improved version of your project. You will be able to gain 30% of the points you did not get in the first submission. For example, assume you got 50 in your first submission. The maximum grade for the report is 95 points, meaning that you were 45 points away from the maximum score. This means that you can gain up to 30% of 45 points, or 14 points. If you got 80 points initially, you can get up to 5 points more, and so on.

**Submitting an improved version is optional.** The goal is not to work towards a perfect delivery, but to make you reflect on your answers and learn from any shortcomings. You should consider the feedback you got from the teachers and from the peer review when working on a revised version. Trivial resubmissions with little improvement will get no bonus points. Bonus points will be awarded if there is improvement, even if the revised answer is not 100% correct. How much improvement is enough? That will be decided on a case-by-case basis. But the bar will not be set very high. 

Bonus points from submitting an improved version will be added to both group members. As in the original submission, both will be asked to submit the new version on Devilry. 

### Example grade calculations

The final grade for each project is calculated by adding the initial grade plus any bonus points plus the peer review points. Here are a few examples of grade calculations:

*Student 1*:

* Initial grade: 65 (out of 95, meaning 30 x 0.3 = 10 maximum bonus points)
* Submitted improved version and got 10 bonus points, grade changed to 75
* Did not submit peer review, grade is unchanged, final grade is 75 + 0 = 75

*Student 2*:

* Initial grade: 45 (out of 95, meaning 50 x 0.3 = 15 maximum bonus points)
* Submitted improved version and got 9 bonus points, grade changed to 54
* Submitted peer review, final grade is 54 + 5 = 59

*Student 3*:

* Initial grade: 90 (out of 95, meaning 5 x 0.3 = 2 maximum bonus points)
* Submitted improved version and got 2 bonus points, grade changed to 92
* Submitted peer review, final grade is 92 + 5 = 97
