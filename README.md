## DAT SF 19 Course Repository

Course materials for [General Assembly's Data Science course](https://generalassemb.ly/education/data-science/san-francisco) in San Francisco (11/30/15 - 3/2/16).

**Instructor:** [Rob Hall](https://generalassemb.ly/instructors/rob-hall/1864)

**EiRs:** Justin Breucop, Devin Brady

### Course Schedule

Week | Monday | Wednesday
--- | --- | ---
 1 | 11/30: [Introduction to Data Science](#class-1-introduction-to-data-science) | 12/2: [Command Line and Version Control](#class-2-command-line-and-version-control)
 2 | 12/7: Intro to Machine Learning with KNN | 12/9: Regression & Regularization
 3 | 12/14: Web APIs & Pandas | 12/16: Decision Trees for Classification & Regression
 N/A | 12/21: Holiday Break **No Class** | 12/23: Holiday Break **No Class**
 N/A | 12/28: Holiday Break **No Class** | 12/30: Holiday Break **No Class**
 4 | 1/4: TBD | 1/6: TBD
 5 | 1/11: TBD | 1/13: TBD
 6 | 1/18: MLK Day **No Class** | 1/20: TBD
 7 | 1/25: TBD | 1/27: TBD
8 | 2/1: TBD | 2/3: TBD
9 | 2/8: TBD | 2/10: TBD
10 | 2/15: President's Day **No Class** | 2/17: TBD
11 | 2/22: TBD | 2/24: TBD |
12 | 2/29: Presentations 1 | 3/2: Presentations 2

_syllabus last updated: 11/29/2015_

### Submission Forms
* [Feedback form](http://bit.ly/dat7feedback)
* [Homework and project submissions](http://bit.ly/dat7homework)

-----

### Class 1: Introduction to Data Science
* Welcome from General Assembly staff
* Course overview ([slides](slides/01_course_overview.pdf))
* Introduction to data science ([slides](slides/01_intro_to_data_science.pdf))
* Discuss the [course project](project/README.md)
* Types of data ([slides](slides/01_types_of_data.pdf)) and [public data sources](project/public_data.md)
* Wrap up: Slack tour, submission forms

**Homework:**
* Work through GA's friendly [command line tutorial](http://generalassembly.github.io/prework/command-line/#/) using Terminal (Linux/Mac) or Git Bash (Windows), and then browse through this [command line reference](code/02_command_line.md).
* Watch videos 1 through 8 (21 minutes) of [Introduction to Git and GitHub](https://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD).
* If your laptop has any setup issues, please work with us to resolve them by Wednesday.

**Resources:**
* For a useful look at the different types of data scientists, read [Analyzing the Analyzers](http://cdn.oreillystatic.com/oreilly/radarreport/0636920029014/Analyzing_the_Analyzers.pdf) (32 pages).
* For some thoughts on what it's like to be a data scientist, read these short posts from [Win-Vector](http://www.win-vector.com/blog/2012/09/on-being-a-data-scientist/) and [Datascope Analytics](http://datascopeanalytics.com/what-we-think/2014/07/31/six-qualities-of-a-great-data-scientist).
* Quora has a [data science topic FAQ](https://www.quora.com/Data-Science) with lots of interesting Q&A.

-----

### Class 2: Command Line and Version Control
* Command line exercise ([code](code/02_command_line.md))
* Git and GitHub ([slides](slides/02_git_github.pdf))
* Intermediate command line
* Wrap up: Course schedule, office hours

**Homework:**
* Complete the homework exercise listed in the [command line introduction](code/02_command_line.md#homework-exercise). Create a Markdown document that includes your answers and the code you used to arrive at those answers. Add this file to a GitHub repo that you'll use for all of your coursework, and submit a link to your repo using the homework submission form.
* Review the code from the [beginner](code/00_python_beginner_workshop.py) and [intermediate](code/00_python_intermediate_workshop.py) Python workshops. If you don't feel comfortable with any of the content (up through the "dictionaries" section), you should spend some time this weekend practicing Python. Here are my recommended resources:
    * If you like learning from a book, [Python for Informatics](http://www.pythonlearn.com/html-270/) has useful chapters on strings, lists, and dictionaries.
    * If you prefer interactive exercises, try these lessons from [Codecademy](http://www.codecademy.com/en/tracks/python): "Python Lists and Dictionaries" and "A Day at the Supermarket".
    * If you have more time, try these much longer lessons from [DataQuest](https://dataquest.io/missions): "Find the US city with the lowest crime rate" and "Discover weather patterns in LA".
    * If you've already mastered these topics and want more of a challenge, try solving the second [Python Challenge](http://www.pythonchallenge.com/) and send me your code in Slack.
* If there are specific Python topics you want me to cover next week, send me a Slack message.

**Git and Markdown Resources:**
* [Pro Git](http://git-scm.com/book/en/v2) is an excellent book for learning Git. Read the first two chapters to gain a deeper understanding of version control and basic commands.
* If you want to practice a lot of Git (and learn many more commands), [Git Immersion](http://gitimmersion.com/) looks promising.
* If you want to understand how to contribute on GitHub, you first have to understand [forks and pull requests](http://www.dataschool.io/simple-guide-to-forks-in-github-and-git/).
* [GitRef](http://gitref.org/) is a great reference guide for Git commands, and [Git quick reference for beginners](http://www.dataschool.io/git-quick-reference-for-beginners/) is a shorter guide with commands grouped by workflow.
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) provides a thorough set of Markdown examples with concise explanations. GitHub's [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) is a simpler and more attractive guide, but is less comprehensive.

**Command Line Resources:**
* If you want to go much deeper into the command line, [Data Science at the Command Line](http://shop.oreilly.com/product/0636920032823.do) is a great book. The [companion website](http://datascienceatthecommandline.com/) provides installation instructions for a "data science toolbox" (a virtual machine with many more command line tools), as well as a long reference guide to popular command line tools.
* If you want to do more at the command line with CSV files, try out [csvkit](http://csvkit.readthedocs.org/), which can be installed via `pip`.

-----

<!--
### Homework Schedule

Please submit completed homework assignments by pushing them to your homework repo under your own userid and then telling us where to find your homework via the [homework submission form](http://goo.gl/forms/QBZBG4P3bm).

HW | Topics | Dataset | Assigned | Due
--- | --- | --- | --- | ---
1 | Data Exploration | titanic | 3/11 | 3/16
2 | KNN & Cross Validation | iris | 3/18 | 3/25
FP1 | Elevator Pitch | N/A | 3/23 | 4/1
3 | Decision Trees | bank | 3/30 (as mandatory) | 4/8 (extended)
4 | Logistic Regression, ROC/AUC, & Imbalanced Classes | spam | 4/13 | 4/20
FP2 | [First Draft](https://github.com/ga-students/DAT_SF_13/blob/master/project/dat_project.md#april-26-first-draft-due) of Final Project | yours | 4/13 | 4/27
FP3 | [Peer Feedback](https://github.com/ga-students/DAT_SF_13/blob/master/project/peer_review_guidelines.md) on FP First Draft | yours | 4/27 | 5/4

### Communication

#### Office Hours

instructor | times available | method
:----------|:-------------------|:--
Ankit      | Wednesday, 6:00 - 6:30 PM | in person before class, slack, hangouts by appointment
Chetan	   | Monday, 6:00 - 6:30 PM | in person before class, hangouts by appointment
Matt       | Thursday, 6:00 - 7:00 PM | in person (at GA in "the concourse"), slack, hangouts by appointment
Rob        | Tues & Thurs, all day   | slack (quickest response) or hangouts by appointment

Please use email or Slack to schedule office hours. Use [office hours] in the subject line as it can help us find the emails easier and reply more quickly.
-->

#### Slack

You've all been invited to use Slack for chat during class and the day. Please consider this the primary way to contact other students. The TAs will be in Slack during class to handle questions. All instructors will be available on Slack during office hours (listed above).