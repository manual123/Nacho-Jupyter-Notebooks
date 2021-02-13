## DAT7 Course Repository

Course materials for [General Assembly's Data Science course](https://generalassemb.ly/education/data-science/washington-dc/) in Washington, DC (6/1/15 - 8/12/15).

**Instructor:** Kevin Markham ([Data School blog](http://www.dataschool.io/), [email newsletter](http://www.dataschool.io/subscribe/), [YouTube channel](https://www.youtube.com/user/dataschool))

### [Course Project](project/README.md)

Monday | Wednesday
--- | ---
6/1: [Introduction to Data Science](#class-1-introduction-to-data-science) | 6/3: [Command Line and Version Control](#class-2-command-line-and-version-control)
6/8: [Data Reading and Cleaning](#class-3-data-reading-and-cleaning) | 6/10: [Exploratory Data Analysis](#class-4-exploratory-data-analysis)
6/15: [Visualization](#class-5-visualization) | 6/17: [Machine Learning](#class-6-machine-learning)
6/22: [Getting Data](#class-7-getting-data)<br>**Project Discussion Deadline** | 6/24: [K-Nearest Neighbors](#class-8-k-nearest-neighbors)<br>**Project Question and Dataset Due**
6/29: [Basic Model Evaluation](#class-9-basic-model-evaluation) | 7/1: [Linear Regression](#class-10-linear-regression)
7/6: [Logistic Regression](#class-11-logistic-regression) | 7/8: [Advanced Model Evaluation](#class-12-advanced-model-evaluation)
7/13: **[First Project Presentation](#class-13-first-project-presentation)** | 7/15: [Naive Bayes and Text Data](#class-14-naive-bayes-and-text-data)
7/20: [Natural Language Processing](#class-15-natural-language-processing) | 7/22: [Kaggle Competition](#class-16-kaggle-competition)
7/27: [Decision Trees](#class-17-decision-trees)<br>**Draft Paper Due** | 7/29: [Ensembling](#class-18-ensembling)
8/3: [Advanced scikit-learn and](#class-19-advanced-scikit-learn-and-clustering)<br>[Clustering](#class-19-advanced-scikit-learn-and-clustering), **Peer Review Due** | 8/5: [Course Review](#class-20-course-review)
8/10: **[Final Project Presentation](#classes-21-and-22-final-project-presentation)** | 8/12: **[Final Project Presentation](#classes-21-and-22-final-project-presentation)**

<!--
### Before the Course Begins
* Install [Git](http://git-scm.com/downloads).
* Create an account on the [GitHub](https://github.com/) website.
    * It is not necessary to download "GitHub for Windows" or "GitHub for Mac"
* Install the [Anaconda distribution](http://continuum.io/downloads) of Python 2.7x.
    * If you choose not to use Anaconda, here is a list of the [Python packages](other/python_packages.md) you will need to install during the course.
* Once you receive an email invitation from Slack, join our "DAT7 team" and add your photo.
* Practice Python using the resources below.
* Attend one or both of our Python workshops, depending on your current skill level: [beginner](https://generalassemb.ly/education/intro-to-python-programming/washington-dc/12239) (Saturday 5/16 10am-2pm) and [intermediate](https://generalassemb.ly/education/python-for-data-science-intermediate/washington-dc/12242) (Saturday 5/30 10am-2pm).
* We would like to check the setup of your laptop before the course begins.
    * You can have your laptop checked after the intermediate Python workshop on Saturday 5/30 (2pm-3pm), at the [15th & K Starbucks](http://www.yelp.com/biz/starbucks-washington-15) on Sunday 5/31 (11am-1pm), or before class on Monday 6/1 (5pm-6:30pm).
    * Alternatively, you can walk through the [setup checklist](other/setup_checklist.md) yourself. In this case, please post a message in the "setupchecklist" channel in Slack noting whether or not you had any issues.
-->

### Python Resources
* [Codecademy's Python course](http://www.codecademy.com/en/tracks/python): Good beginner material, including tons of in-browser exercises.
* [DataQuest](https://dataquest.io/): Similar interface to Codecademy, but focused on teaching Python in the context of data science.
* [Google's Python Class](https://developers.google.com/edu/python/): Slightly more advanced, including hours of useful lecture videos and downloadable exercises (with solutions).
* [A Crash Course in Python for Scientists](http://nbviewer.ipython.org/gist/rpmuller/5920182): Read through the Overview section for a quick introduction to Python.
* [Python for Informatics](http://www.pythonlearn.com/book.php): A very beginner-oriented book, with associated [slides](https://drive.google.com/folderview?id=0B7X1ycQalUnyal9yeUx3VW81VDg&usp=sharing) and [videos](https://www.youtube.com/playlist?list=PLlRFEj9H3Oj4JXIwMwN1_ss1Tk8wZShEJ).
* [Beginner](code/00_python_beginner_workshop.py) and [intermediate](code/00_python_intermediate_workshop.py) workshop code: Useful for review and reference.
* [Python 2.7x Reference Guide](https://github.com/justmarkham/python-reference/blob/master/reference.py): Kevin's beginner-oriented guide that demonstrates a ton of Python concepts through short, well-commented examples.
* [Python Tutor](http://pythontutor.com/): Allows you to visualize the execution of Python code.

### Submission Forms
* [Feedback form](http://bit.ly/dat7feedback)
* [Homework and project submissions](http://bit.ly/dat7homework)

### [What's next?](other/advice.md)

### [Additional resources](#bonus-resources)

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
* Keep up with local data-related events through the Data Community DC [event calendar](http://www.datacommunitydc.org/calendar) or [weekly newsletter](http://www.datacommunitydc.org/newsletter).

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
* [GitRef](http://gitref.org/) is my favorite reference guide for Git commands, and [Git quick reference for beginners](http://www.dataschool.io/git-quick-reference-for-beginners/) is a shorter guide with commands grouped by workflow.
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) provides a thorough set of Markdown examples with concise explanations. GitHub's [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) is a simpler and more attractive guide, but is less comprehensive.

**Command Line Resources:**
* If you want to go much deeper into the command line, [Data Science at the Command Line](http://shop.oreilly.com/product/0636920032823.do) is a great book. The [companion website](http://datascienceatthecommandline.com/) provides installation instructions for a "data science toolbox" (a virtual machine with many more command line tools), as well as a long reference guide to popular command line tools.
* If you want to do more at the command line with CSV files, try out [csvkit](http://csvkit.readthedocs.org/), which can be installed via `pip`.

-----

### Class 3: Data Reading and Cleaning
* Git and GitHub assorted tips ([slides](slides/02_git_github.pdf))
* Review command line homework ([solution](code/02_command_line.md#homework-solution))
* Python:
    * Spyder interface
    * Review of list comprehensions
    * Lesson on file reading with airline safety data ([code](code/03_file_reading.py), [data](data/airlines.csv), [article](http://fivethirtyeight.com/features/should-travelers-avoid-flying-airlines-that-have-had-crashes-in-the-past/))
    * Data cleaning exercise
    * Walkthrough of homework with Chipotle order data ([code](code/03_python_homework_chipotle.py), [data](data/chipotle.tsv), [article](http://www.nytimes.com/interactive/2015/02/17/upshot/what-do-people-actually-order-at-chipotle.html))

**Homework:**
* Complete the [homework assignment](code/03_python_homework_chipotle.py) with the [Chipotle data](data/chipotle.tsv), and add a commented Python script to your GitHub repo. If you are unable to complete a part, try writing some pseudocode instead! You have until Monday to complete this assignment.

**Resources:**
* [PEP 8](https://www.python.org/dev/peps/pep-0008/) is Python's "classic" style guide, and is worth a read if you want to write readable code that is consistent with the rest of the Python community.

-----

### Class 4: Exploratory Data Analysis
* Pandas ([code](code/04_pandas.py)):
    * MovieLens 100k movie ratings ([data](data/u.user), [data dictionary](http://files.grouplens.org/datasets/movielens/ml-100k-README.txt), [website](http://grouplens.org/datasets/movielens/))
    * Alcohol consumption by country ([data](data/drinks.csv), [article](http://fivethirtyeight.com/datalab/dear-mona-followup-where-do-people-drink-the-most-beer-wine-and-spirits/))
    * Reports of UFO sightings ([data](data/ufo.csv), [website](http://www.nuforc.org/webreports.html))

**Homework:**
* Complete "Exercise Three" from today's Pandas script. **Note:** You do not need to submit this assignment.
* Read [How Software in Half of NYC Cabs Generates $5.2 Million a Year in Extra Tips](http://iquantny.tumblr.com/post/107245431809/how-software-in-half-of-nyc-cabs-generates-5-2) for an excellent example of exploratory data analysis.

**Resources:**
* Browsing or searching the Pandas [API Reference](http://pandas.pydata.org/pandas-docs/stable/api.html) is an excellent way to locate a function even if you don't know its exact name.
* [What I do when I get a new data set as told through tweets](http://simplystatistics.org/2014/06/13/what-i-do-when-i-get-a-new-data-set-as-told-through-tweets/) is a fun (yet enlightening) look at the process of exploratory data analysis.

-----

### Class 5: Visualization
* Part 2 of Exploratory Data Analysis with Pandas ([code](code/04_pandas.py))
* Visualization with Pandas and Matplotlib ([code](code/05_pandas_visualization.py))

**Homework:**
* Complete the [homework assignment](code/05_pandas_homework_imdb.py) with the [IMDb data](data/imdb_1000.csv), and add a Python script to your GitHub repo. This assignment is due next Monday.

**Pandas Resources:**
* To learn more Pandas, review this [three-part tutorial](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/), or review these two excellent (but extremely long) notebooks on Pandas: [introduction](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_5-Introduction-to-Pandas.ipynb) and [data wrangling](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_6-Data-Wrangling-with-Pandas.ipynb).
* If you want to go really deep into Pandas (and NumPy), read the book [Python for Data Analysis](http://shop.oreilly.com/product/0636920023784.do) by the creator of Pandas.
* Here are examples of different types of [joins in Pandas](http://www.gregreda.com/2013/10/26/working-with-pandas-dataframes/#joining), for when you need to figure out how to merge two DataFrames.

**Visualization Resources:**
* Watch [Look at Your Data](https://www.youtube.com/watch?v=coNDCIMH8bk) (18 minutes) for an excellent example of why visualization is useful for understanding your data.
* For more on Pandas plotting, read this [notebook](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_7-Plotting-with-Pandas.ipynb) or the [visualization page](http://pandas.pydata.org/pandas-docs/stable/visualization.html) from the official Pandas documentation.
* To learn how to customize your plots further, browse through this [notebook on matplotlib](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_4-Matplotlib.ipynb) or this [similar notebook](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb).
* To explore different types of visualizations and when to use them, [Choosing a Good Chart](http://extremepresentation.typepad.com/files/choosing-a-good-chart-09.pdf) and [The Graphic Continuum](http://www.coolinfographics.com/storage/post-images/The-Graphic-Continuum-POSTER.jpg) are nice one-page references, and the interactive [R Graph Catalog](http://shinyapps.stat.ubc.ca/r-graph-catalog/) has handy filtering capabilities.
* This [PowerPoint presentation](http://www2.research.att.com/~volinsky/DataMining/Columbia2011/Slides/Topic2-EDAViz.ppt) from Columbia's Data Mining class contains lots of good advice for properly using different types of visualizations.

-----

### Class 6: Machine Learning
* Review Python homework with the Chipotle data ([solution](code/03_python_homework_chipotle.py), [detailed explanation](http://nbviewer.ipython.org/github/Alexjmsherman/DAT7/blob/master/Python%20Homework%20with%20Chipotle%20data%20answers.ipynb))
* Grouped box plots and grouped histograms ([code](code/05_pandas_visualization.py))
* Human learning exercise:
    * [Iris dataset](http://archive.ics.uci.edu/ml/datasets/Iris) hosted by the UCI Machine Learning Repository
    * [Iris photo](http://sebastianraschka.com/Images/2014_python_lda/iris_petal_sepal.png)
    * [Solution](code/06_human_learning_iris.py)
* Introduction to machine learning ([slides](slides/06_machine_learning.pdf))
* Course project:
    * [Example projects](https://github.com/justmarkham/DAT-project-examples)
    * Project question exercise

**Homework:**
* Your deadline for discussing your project ideas with an instructor is Monday, and your project question and dataset is due Wednesday.

**Resources:**
* For a very quick summary of the key points about machine learning, watch [What is machine learning, and how does it work?](https://www.youtube.com/watch?v=elojMnjn4kk) (10 minutes) or read the associated [notebook](http://nbviewer.ipython.org/github/justmarkham/scikit-learn-videos/blob/master/01_machine_learning_intro.ipynb).
* For a more in-depth introduction to machine learning, read section 2.1 (14 pages) of Hastie and Tibshirani's excellent book, [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/). (It's a free PDF download!)
* For a really nice comparison of supervised versus unsupervised learning, plus an introduction to reinforcement learning, watch this [video](http://work.caltech.edu/library/014.html) (13 minutes) from Caltech's [Learning From Data](http://work.caltech.edu/telecourse.html) course.
* For a preview of some of the machine learning content we will cover during the course, read Sebastian Raschka's [overview of the supervised learning process](https://github.com/rasbt/pattern_classification/blob/master/machine_learning/supervised_intro/introduction_to_supervised_machine_learning.md).
* [The Emoji Translation Project](https://www.kickstarter.com/projects/fred/the-emoji-translation-project) is a really fun application of machine learning.
* Look up the [characteristics of your zip code](http://www.esri.com/landing-pages/tapestry/), and then read about the [67 distinct segments](http://doc.arcgis.com/en/esri-demographics/data/tapestry-segmentation.htm) in detail.

-----

### Class 7: Getting Data
* Pandas homework with the IMDb data due ([solution](code/05_pandas_homework_imdb.py))
* APIs ([code](code/07_api.py))
    * [OMDb API](http://www.omdbapi.com/)
* Web scraping ([code](code/07_web_scraping.py))
    * [IMDb: robots.txt](http://www.imdb.com/robots.txt)
    * [Example web page](data/example.html)
    * [IMDb: The Shawshank Redemption](http://www.imdb.com/title/tt0111161/)

**Homework:**
* Your project question and dataset is due on Wednesday.
* **Optional:** Complete the homework exercise listed in the [web scraping code](code/07_web_scraping.py). It will take the place of any one homework you miss, past or future!
* If you're not using Anaconda, [install the IPython Notebook](http://ipython.org/install.html) using `pip`. (The IPython Notebook comes with Anaconda.)
* If you're not using Anaconda, [install Seaborn](http://stanford.edu/~mwaskom/software/seaborn/installing.html) using `pip`. If you're using Anaconda, install Seaborn by running `conda install seaborn` at the command line.
* Watch this brief introduction to [scikit-learn and the IPython Notebook](https://www.youtube.com/watch?v=IsXXlYVBt1M) (15 minutes), and try to follow along with the Notebook introduction on your own computer.
* Read Kevin's [introduction to reproducibility](http://www.dataschool.io/reproducibility-is-not-just-for-researchers/), read Jeff Leek's [guide to creating a reproducible analysis](https://github.com/jtleek/datasharing), and watch this related [Colbert Report video](http://thecolbertreport.cc.com/videos/dcyvro/austerity-s-spreadsheet-error) (8 minutes).

**API Resources:**
* [Mashape](https://www.mashape.com/explore) and [Apigee](https://apigee.com/providers) allow you to explore tons of different APIs. Alternatively, a [Python API wrapper](http://www.pythonforbeginners.com/api/list-of-python-apis) is available for many popular APIs.
* [API Integration in Python](https://realpython.com/blog/python/api-integration-in-python/) provides a very readable introduction to REST APIs.
* Microsoft's [Face Detection API](https://www.projectoxford.ai/demo/face#detection), which powers [How-Old.net](http://how-old.net/), is a great example of how a machine learning API can be leveraged to produce a compelling web application.

**Web Scraping Resources:**
* The [Beautiful Soup documentation](http://www.crummy.com/software/BeautifulSoup/bs4/doc/) is incredibly thorough, but is hard to use as a reference guide. However, the section on [specifying a parser](http://www.crummy.com/software/BeautifulSoup/bs4/doc/#specifying-the-parser-to-use) may be helpful if Beautiful Soup appears to be parsing a page incorrectly.
* For more Beautiful Soup examples and tutorials, see [Web Scraping 101 with Python](http://www.gregreda.com/2013/03/03/web-scraping-101-with-python/), Alex's well-commented notebook on [scraping Craigslist](http://nbviewer.ipython.org/github/Alexjmsherman/DataScience_GeneralAssembly/blob/master/Final_Project/1.%20Final_Project_Data%20Scraping.ipynb), this [notebook](http://web.stanford.edu/~zlotnick/TextAsData/Web_Scraping_with_Beautiful_Soup.html) from Stanford's Text As Data course, and this [notebook](http://nbviewer.ipython.org/github/cs109/2014/blob/master/lectures/2014_09_23-lecture/data_scraping_transcript.ipynb) and associated [video](http://cm.dce.harvard.edu/2015/01/14328/L07/screen_H264LargeTalkingHead-16x9.shtml) from Harvard's Data Science course.
* For a much longer web scraping tutorial covering Beautiful Soup, lxml, XPath, and Selenium, watch [Web Scraping with Python](https://www.youtube.com/watch?v=p1iX0uxM1w8) (3 hours 23 minutes) from PyCon 2014. The [slides](https://docs.google.com/presentation/d/1uHM_esB13VuSf7O1ScGueisnrtu-6usGFD3fs4z5YCE/edit#slide=id.p) and [code](https://github.com/kjam/python-web-scraping-tutorial) are also available.
* For more complex web scraping projects, [Scrapy](http://scrapy.org/) is a popular application framework that works with Python. It has excellent [documentation](http://doc.scrapy.org/en/1.0/index.html), and here's a [tutorial](https://github.com/rdempsey/ddl-data-wrangling) with detailed slides and code.
* [robotstxt.org](http://www.robotstxt.org/robotstxt.html) has a concise explanation of how to write (and read) the `robots.txt` file.
* [import.io](https://import.io/) and [Kimono](https://www.kimonolabs.com/) claim to allow you to scrape websites without writing any code.
* [How a Math Genius Hacked OkCupid to Find True Love](http://www.wired.com/2014/01/how-to-hack-okcupid/all/) and [How Netflix Reverse Engineered Hollywood](http://www.theatlantic.com/technology/archive/2014/01/how-netflix-reverse-engineered-hollywood/282679/?single_page=true) are two fun examples of how web scraping has been used to build interesting datasets.

-----

### Class 8: K-Nearest Neighbors
* Optional web scraping homework due ([solution](code/07_web_scraping.py))
* Reproducibility
    * Discuss assigned readings: [introduction](http://www.dataschool.io/reproducibility-is-not-just-for-researchers/), [Colbert Report video](http://thecolbertreport.cc.com/videos/dcyvro/austerity-s-spreadsheet-error), [cabs article](http://iquantny.tumblr.com/post/107245431809/how-software-in-half-of-nyc-cabs-generates-5-2), [Tweet](https://twitter.com/jakevdp/status/519563939177197571), [creating a reproducible analysis](https://github.com/jtleek/datasharing)
    * Examples: [Classic rock](https://github.com/fivethirtyeight/data/tree/master/classic-rock), [student project 1](https://github.com/jwknobloch/DAT4_final_project), [student project 2](https://github.com/justmarkham/DAT4-students/tree/master/Jonathan_Bryan/Project_Files)
* Machine learning exercise ([article](http://blog.dominodatalab.com/10-interesting-uses-of-data-science/))
* Brief introduction to the IPython Notebook
* K-nearest neighbors and scikit-learn ([notebook](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/08_knn_sklearn.ipynb), [notebook code](code/08_knn_sklearn_nb.py))
* Exploring the bias-variance tradeoff ([notebook](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/08_bias_variance.ipynb), [notebook code](code/08_bias_variance_nb.py))

**Homework:**
* Reading assignment on the [bias-variance tradeoff](homework/09_bias_variance.md)
* Browse through the scikit-learn documentation for KNN to get a sense of how it's organized: [user guide](http://scikit-learn.org/stable/modules/neighbors.html), [module reference](http://scikit-learn.org/stable/modules/classes.html#module-sklearn.neighbors), [class documentation](http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
* Work on your project... your first project presentation is in less than three weeks!
* **Optional:** Read the [Teaching Assistant Evaluation dataset](https://archive.ics.uci.edu/ml/datasets/Teaching+Assistant+Evaluation) into Pandas, create the X and y objects (the response variable is "class attribute"), and go through scikit-learn's 4-step modeling process. (There's no need to submit your code unless you have a question or would like feedback!)

**KNN Resources:**
* For a recap of the key points about KNN and scikit-learn, watch [Getting started in scikit-learn with the famous iris dataset](https://www.youtube.com/watch?v=hd1W4CyPX58) (15 minutes) and [Training a machine learning model with scikit-learn](https://www.youtube.com/watch?v=RlQuVL6-qe8) (20 minutes).
* [A Detailed Introduction to KNN](https://saravananthirumuruganathan.wordpress.com/2010/05/17/a-detailed-introduction-to-k-nearest-neighbor-knn-algorithm/) is a bit dense, but provides a more thorough introduction to KNN and its applications.
* This lecture on [Image Classification](http://cs231n.github.io/classification/) shows how KNN could be used for detecting similar images, and also touches on topics we will cover in future classes (hyperparameter tuning and cross-validation).
* Some applications for which KNN is well-suited are [object recognition](http://vlm1.uta.edu/~athitsos/nearest_neighbors/), [satellite image enhancement](http://land.umn.edu/documents/FS6.pdf), [document categorization](http://www.ceng.metu.edu.tr/~e120321/paper.pdf), and [gene expression analysis](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.208.993).

**Reproducibility Resources:**
* [Software development skills for data scientists](http://treycausey.com/software_dev_skills.html) discusses the importance of writing functions and proper code comments (among other skills), which are highly useful for creating a reproducible analysis.
* [Data science done well looks easy - and that is a big problem for data scientists](http://simplystatistics.org/2015/03/17/data-science-done-well-looks-easy-and-that-is-a-big-problem-for-data-scientists/) explains how a reproducible analysis demonstrates all of the work that goes into proper data science.

**Other Resources:**
* If you would like to learn the IPython Notebook, the official [Notebook tutorials](http://nbviewer.ipython.org/github/ipython/ipython/blob/master/examples/Notebook/Index.ipynb) are useful.
* To get started with Seaborn for visualization, the official website has a series of [tutorials](http://web.stanford.edu/~mwaskom/software/seaborn/tutorial.html) and an [example gallery](http://web.stanford.edu/~mwaskom/software/seaborn/examples/index.html).

-----

### Class 9: Basic Model Evaluation
* Discuss the reading assignment on the [bias-variance tradeoff](homework/09_bias_variance.md)
* Model evaluation using train/test split ([notebook](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/09_model_evaluation.ipynb), [notebook code](code/09_model_evaluation_nb.py))
* Glass identification exercise using scikit-learn ([instructions](homework/09_glass_id.md), [code](code/09_glass_id.py))

**Homework:**
* Try to finish the glass identification exercise at home, and then compare your code to the [solution](code/09_glass_id.py). However, there is no need to submit your code unless you have questions or would like feedback.
* If you're brand new to linear regression, read [What is Linear Regression?](http://blog.yhathq.com/posts/what-is-linear-regression.html) and watch [The Easiest Introduction to Regression Analysis](https://www.youtube.com/watch?v=k_OB1tWX9PM) (14 minutes).

**Resources:**
* For a recap of much of today's lesson, watch [Comparing machine learning models in scikit-learn](https://www.youtube.com/watch?v=0pP4EwWJgIU) (27 minutes).
* For another explanation of training error versus testing error, the bias-variance tradeoff, and train/test split (also known as the "validation set approach"), watch Hastie and Tibshirani's video on [estimating prediction error](https://www.youtube.com/watch?v=_2ij6eaaSl0&t=2m34s) (12 minutes, starting at 2:34).
* Caltech's Learning From Data course includes a fantastic video on [visualizing bias and variance](http://work.caltech.edu/library/081.html) (15 minutes).
* [Random Test/Train Split is Not Always Enough](http://www.win-vector.com/blog/2015/01/random-testtrain-split-is-not-always-enough/) explains why random train/test split may not be a suitable model evaluation procedure if your data has a significant time element.

-----

### Class 10: Linear Regression
* Linear regression ([notebook](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/10_linear_regression.ipynb), [notebook code](code/10_linear_regression_nb.py))

**Homework:**
* Complete the [homework assignment](homework/10_yelp_reviews.md) with the [Yelp reviews data](data/yelp.csv), and add a Python script (or IPython notebook) to your GitHub repo. This assignment is due on Monday.
* Watch Rahul Patwari's videos on [probability](https://www.youtube.com/watch?v=o4QmoNfW3bI) (5 minutes) and [odds](https://www.youtube.com/watch?v=GxbXQjX7fC0) (8 minutes) if you're not familiar with either of those terms.
* Read these excellent articles from BetterExplained: [An Intuitive Guide To Exponential Functions & e](http://betterexplained.com/articles/an-intuitive-guide-to-exponential-functions-e/) and [Demystifying the Natural Logarithm (ln)](http://betterexplained.com/articles/demystifying-the-natural-logarithm-ln/).

**Resources:**
* Setosa has an excellent [interactive visualization](http://setosa.io/ev/ordinary-least-squares-regression/) of linear regression.
* To go much more in-depth on linear regression, read Chapter 3 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), from which this lesson was adapted. Alternatively, watch the [related videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) or read my [quick reference guide](http://www.dataschool.io/applying-and-interpreting-linear-regression/) to the key points in that chapter.
* To learn more about Statsmodels and how to interpret the output, DataRobot has some decent posts on [simple linear regression](http://www.datarobot.com/blog/ordinary-least-squares-in-python/) and [multiple linear regression](http://www.datarobot.com/blog/multiple-regression-using-statsmodels/).
* This [introduction to linear regression](http://people.duke.edu/~rnau/regintro.htm) is much more detailed and mathematically thorough, and includes lots of good advice.
* This is a relatively quick post on the [assumptions of linear regression](http://pareonline.net/getvn.asp?n=2&v=8).
* John Rauser's talk on [Statistics Without the Agonizing Pain](https://www.youtube.com/watch?v=5Dnw46eC-0o) (12 minutes) gives a great explanation of how the null hypothesis is rejected.
* A major scientific journal recently banned the use of p-values:
    * Scientific American has a nice [summary](http://www.scientificamerican.com/article/scientists-perturbed-by-loss-of-stat-tools-to-sift-research-fudge-from-fact/) of the ban.
    * This [response](http://www.nature.com/news/statistics-p-values-are-just-the-tip-of-the-iceberg-1.17412) to the ban in Nature argues that "decisions that are made earlier in data analysis have a much greater impact on results".
    * Andrew Gelman has a readable [paper](http://www.stat.columbia.edu/~gelman/research/unpublished/p_hacking.pdf) in which he argues that "it's easy to find a p < .05 comparison even if nothing is going on, if you look hard enough".

-----

### Class 11: Logistic Regression
* Yelp reviews homework due ([solution](code/10_yelp_reviews.py))
* Logistic regression ([notebook](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/11_logistic_regression.ipynb), [notebook code](code/11_logistic_regression_nb.py))
* Exercise with Titanic data ([instructions](homework/11_titanic.md), [solution](code/11_titanic.py))
* Confusion matrix ([slides](slides/11_confusion_matrix.pdf))

**Homework:**
* If you aren't yet comfortable with all of the confusion matrix terminology, watch Rahul Patwari's videos on [Intuitive sensitivity and specificity](https://www.youtube.com/watch?v=U4_3fditnWg) (9 minutes) and [The tradeoff between sensitivity and specificity](https://www.youtube.com/watch?v=vtYDyGGeQyo) (13 minutes).
* Video assignment on [ROC curves and AUC](homework/12_roc_auc.md)

**Resources:**
* To go deeper into logistic regression, read the first three sections of Chapter 4 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), or watch the [first three videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) (30 minutes) from that chapter.
* For a math-ier explanation of logistic regression, watch the first seven videos (71 minutes) from week 3 of Andrew Ng's [machine learning course](https://www.coursera.org/learn/machine-learning/home/info), or read the [related lecture notes](http://www.holehouse.org/mlclass/06_Logistic_Regression.html) compiled by a student.
* For more on interpreting logistic regression coefficients, read this excellent [guide](http://www.ats.ucla.edu/stat/mult_pkg/faq/general/odds_ratio.htm) by UCLA's IDRE and these [lecture notes](http://www.unm.edu/~schrader/biostat/bio2/Spr06/lec11.pdf) from the University of New Mexico.
* The scikit-learn documentation has a nice [explanation](http://scikit-learn.org/stable/modules/calibration.html) of what it means for a predicted probability to be calibrated.
* [Supervised learning superstitions cheat sheet](http://ryancompton.net/assets/ml_cheat_sheet/supervised_learning.html) is a very nice comparison of four classifiers we cover in the course (logistic regression, decision trees, KNN, Naive Bayes) and one classifier we do not cover (Support Vector Machines).
* My [simple guide to confusion matrix terminology](http://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/) may be useful to you as a reference.

-----

### Class 12: Advanced Model Evaluation
* Advanced model evaluation ([notebook](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/12_advanced_model_evaluation.ipynb), [notebook code](code/12_advanced_model_evaluation_nb.py))
    * Null accuracy, handling missing values
    * Confusion matrix
    * Handling categorical features
* ROC curves and AUC
    * Discuss the [video assignment](homework/12_roc_auc.md)
    * Exercise: drawing an ROC curve ([slides](slides/12_drawing_roc.pdf))
    * Return to the notebook

**Homework:**
* Your first project presentation is on Monday! Please submit a link to your project repository (with slides, code, data, and visualizations) before class using the submission form.

**ROC Resources:**
* Rahul Patwari has a great video on [ROC Curves](https://www.youtube.com/watch?v=21Igj5Pr6u4) (12 minutes).
* [An introduction to ROC analysis](http://people.inf.elte.hu/kiss/13dwhdm/roc.pdf) is a very readable paper on the topic.
* These [lesson notes](http://ebp.uga.edu/courses/Chapter%204%20-%20Diagnosis%20I/8%20-%20ROC%20curves.html) from a course at the University of Georgia include some simple, real-world examples of the use of ROC curves.
* ROC curves can be used across a wide variety of applications, such as [comparing different feature sets](http://research.microsoft.com/pubs/205472/aisec10-leontjeva.pdf) for detecting fraudulent Skype users, and [comparing different classifiers](http://www.cse.ust.hk/nevinZhangGroup/readings/yi/Bradley_PR97.pdf) on a number of popular datasets.
* This blog post about [Amazon Machine Learning](https://aws.amazon.com/blogs/aws/amazon-machine-learning-make-data-driven-decisions-at-scale/) contains a neat [graphic](https://media.amazonwebservices.com/blog/2015/ml_adjust_model_1.png) showing how classification threshold affects different evaluation metrics.
* This short notebook demonstrates how ROC curves and AUC are only sensitive to the [rank ordering of predicted probabilities](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/12_roc_auc_rank_ordering.ipynb).

**Other Resources:**
* scikit-learn has extensive documentation on [model evaluation](http://scikit-learn.org/stable/modules/model_evaluation.html).
* Section 3.3.1 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (4 pages) has a great explanation of dummy encoding for categorical features.

-----

### Class 13: First Project Presentation
* Project presentations!

**Homework:**
* Reading assignment on [spam filtering](homework/14_spam_filtering.md)
* Read these [Introduction to Probability](https://docs.google.com/presentation/d/1cM2dVbJgTWMkHoVNmYlB9df6P2H8BrjaqAcZTaLe9dA/edit#slide=id.gfc3caad2_00) slides, or skim section 2.1 of the [OpenIntro Statistics textbook](https://www.openintro.org/stat/textbook.php) (12 pages). Pay specific attention to the following terms: probability, mutually exclusive, sample space, independent.
* **Optional:** Try to gain an understanding of conditional probability from this [visualization](http://setosa.io/conditional/).
* **Optional:** For an intuitive introduction to Bayes' theorem, read these posts on [wealth and happiness](http://www.quora.com/What-is-an-intuitive-explanation-of-Bayes-Rule/answer/Michael-Hochster), [ducks](https://planspacedotorg.wordpress.com/2014/02/23/bayes-rule-for-ducks/), or [legos](http://www.countbayesie.com/blog/2015/2/18/bayes-theorem-with-lego).

-----

### Class 14: Naive Bayes and Text Data
* Conditional probability and Bayes' theorem
    * [Slides](slides/14_bayes_theorem.pdf) (adapted from [Visualizing Bayes' theorem](http://oscarbonilla.com/2009/05/visualizing-bayes-theorem/))
    * Applying Bayes' theorem to iris classification ([notebook](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/14_bayes_theorem_iris.ipynb))
* Naive Bayes classification
    * [Slides](slides/14_naive_bayes.pdf)
    * Example with spam filtering ([notebook](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/14_naive_bayes_spam.ipynb))
    * Discuss the reading assignment on [spam filtering](homework/14_spam_filtering.md)
    * Classifying [SMS messages](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection) ([code](code/14_naive_bayes.py))

**Homework:**
* Confirm that you have [TextBlob](https://textblob.readthedocs.org/) installed by running `import textblob` from within your preferred Python environment. If it's not installed, run `pip install textblob` at the command line (not from within Python).
* Complete the [Yelp review text homework](homework/14_yelp_text.md), and add a Python script (or IPython notebook) to your GitHub repo. This assignment is due on Monday.
* There is a video/reading assignment on [cross-validation](homework/15_cross_validation.md), for those of you that have not already watched the video or would prefer a reading instead.

**Resources:**
* For more on conditional probability, read these [slides](https://docs.google.com/presentation/d/1psUIyig6OxHQngGEHr3TMkCvhdLInnKnclQoNUr4G4U/edit#slide=id.gfc69f484_00), or read section 2.2 of the [OpenIntro Statistics textbook](https://www.openintro.org/stat/textbook.php) (14 pages).
* For an intuitive explanation of Naive Bayes classification, read this post on [airport security](http://www.quora.com/In-laymans-terms-how-does-Naive-Bayes-work/answer/Konstantin-Tt).
* For more details on Naive Bayes classification, Wikipedia has two excellent articles ([Naive Bayes classifier](http://en.wikipedia.org/wiki/Naive_Bayes_classifier) and [Naive Bayes spam filtering](http://en.wikipedia.org/wiki/Naive_Bayes_spam_filtering)), and Cross Validated has a good [Q&A](http://stats.stackexchange.com/questions/21822/understanding-naive-bayes).
* When applying Naive Bayes classification to a dataset with continuous features, it is best to use [GaussianNB](http://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.GaussianNB.html) rather than [MultinomialNB](http://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html). Wikipedia has a short [description](https://en.wikipedia.org/wiki/Naive_Bayes_classifier#Gaussian_naive_Bayes) of Gaussian Naive Bayes, as well as an excellent [example](https://en.wikipedia.org/wiki/Naive_Bayes_classifier#Sex_classification) of its usage.
* These [slides](http://www.umiacs.umd.edu/~jbg/teaching/DATA_DIGGING/lecture_05.pdf) from the University of Maryland provide more mathematical details on both logistic regression and Naive Bayes, and also explain how Naive Bayes is actually a "special case" of logistic regression.
* Andrew Ng has a [paper](https://cs.stanford.edu/people/ang//papers/nips01-discriminativegenerative.pdf) comparing the performance of logistic regression and Naive Bayes across a variety of datasets.
* If you enjoyed Paul Graham's article, you can read [his follow-up article](http://www.paulgraham.com/better.html) on how he improved his spam filter and this [related paper](http://www.merl.com/publications/docs/TR2004-091.pdf) about state-of-the-art spam filtering in 2004.

-----

### Class 15: Natural Language Processing
* Yelp review text homework due ([solution](code/14_yelp_text.py))
* Natural language processing ([notebook](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/15_natural_language_processing.ipynb), [notebook code](code/15_natural_language_processing_nb.py))
* Cross-validation
    * Discuss the [video/reading assignment](homework/15_cross_validation.md) ([notebook](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/15_cross_validation.ipynb), [notebook code](code/15_cross_validation_nb.py))
* Introduction to our Kaggle competition
    * Create a [Kaggle](https://www.kaggle.com/) account, join the [competition](https://inclass.kaggle.com/c/dat7-stack-overflow) using the invitation link, download the sample submission, and then submit the sample submission (which will require SMS account verification).

**Homework:**
* Download the competition files, move them to the `DAT7/data` directory, and make sure you can open the CSV files using Pandas. If you have any problems opening the files, you probably need to turn off real-time virus scanning (especially Microsoft Security Essentials).
* Come up with some theories about which features might be relevant to predicting the response, and then explore the data to see if those theories appear to be true.
* **Optional:** Think about some features that might be worth creating from the data, and then figure out how to actually create those features.
* **Optional:** Watch my [project presentation video](https://www.youtube.com/watch?v=HGr1yQV3Um0) (16 minutes) for a tour of the end-to-end machine learning process for a Kaggle competition, including the creation of new features. (Or, just read through the [slides](https://speakerdeck.com/justmarkham/allstate-purchase-prediction-challenge-on-kaggle).)

**NLP Resources:**
* If you want to learn a lot more NLP, check out the excellent [video lectures](https://class.coursera.org/nlp/lecture) and [slides](http://web.stanford.edu/~jurafsky/NLPCourseraSlides.html) from this [Coursera course](https://www.coursera.org/course/nlp) (which is no longer being offered).
* This slide deck defines many of the [key NLP terms](https://github.com/ga-students/DAT_SF_9/blob/master/16_Text_Mining/DAT9_lec16_Text_Mining.pdf).
* [Natural Language Processing with Python](http://www.nltk.org/book/) is the most popular book for going in-depth with the [Natural Language Toolkit](http://www.nltk.org/) (NLTK).
* [A Smattering of NLP in Python](http://nbviewer.ipython.org/github/charlieg/A-Smattering-of-NLP-in-Python/blob/master/A%20Smattering%20of%20NLP%20in%20Python.ipynb) provides a nice overview of NLTK, as does this [notebook from DAT5](http://nbviewer.ipython.org/github/justmarkham/DAT5/blob/master/notebooks/14_nlp.ipynb).
* [spaCy](https://honnibal.github.io/spaCy/) is a newer Python library for text processing that is focused on performance (unlike NLTK).
* If you want to get serious about NLP, [Stanford CoreNLP](http://nlp.stanford.edu/software/corenlp.shtml) is a suite of tools (written in Java) that is highly regarded.
* [DC Natural Language Processing](http://www.meetup.com/DC-NLP/) is an active Meetup group in our local area.

**Cross-Validation Resources:**
* For more on cross-validation, read section 5.1 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (11 pages) or watch the related videos: [K-fold and leave-one-out cross-validation](https://www.youtube.com/watch?v=nZAM5OXrktY) (14 minutes), [cross-validation the right and wrong ways](https://www.youtube.com/watch?v=S06JpVoNaA0) (10 minutes).
* [Accurately Measuring Model Prediction Error](http://scott.fortmann-roe.com/docs/MeasuringError.html) compares adjusted R-squared, AIC and BIC, train/test split, and cross-validation.
* If you want to understand the different variations of cross-validation, this [paper](http://www.jcheminf.com/content/pdf/1758-2946-6-10.pdf) examines and compares them in detail.

-----

### Class 16: Kaggle Competition
* Overview of how Kaggle works ([slides](slides/16_kaggle.pdf))
* Kaggle In-Class competition: [Predict whether a Stack Overflow question will be closed](https://inclass.kaggle.com/c/dat7-stack-overflow)
    * [Complete code file](code/16_kaggle.py)
    * [Minimal code file](code/16_kaggle_minimal.py): excludes all exploratory code
    * [Explanations of log loss](http://www.quora.com/What-is-an-intuitive-explanation-for-the-log-loss-function)

**Homework:**
* Your draft paper is due on Monday! Please submit a link to your project repository (with paper, code, data, and visualizations) before class using the submission form.
* **Optional:** Keep working on this competition! You can make up to 5 submissions per day, and the competition doesn't close until 6:30pm ET on Wednesday, August 5 (class 20).

**Resources:**
* For a great overview of the diversity of problems tackled by Kaggle competitions, watch [Kaggle Transforms Data Science Into Competitive Sport](https://www.youtube.com/watch?v=8w4UY66GKcM) (28 minutes) by Jeremy Howard (past president of Kaggle).
* [Getting in Shape for the Sport of Data Science](https://www.youtube.com/watch?v=kwt6XEh7U3g) (74 minutes), also by Jeremy Howard, contains a lot of tips for competitive machine learning.
* [Learning from the best](http://blog.kaggle.com/2014/08/01/learning-from-the-best/) is an excellent blog post covering top tips from Kaggle Masters on how to do well on Kaggle.
* [Feature Engineering Without Domain Expertise](https://www.youtube.com/watch?v=bL4b1sGnILU) (17 minutes), a talk by Kaggle Master Nick Kridler, provides some simple advice about how to iterate quickly and where to spend your time during a Kaggle competition.
* These examples may help you to better understand the process of feature engineering: predicting the number of [passengers at a train station](https://medium.com/@chris_bour/french-largest-data-science-challenge-ever-organized-shows-the-unreasonable-effectiveness-of-open-8399705a20ef), identifying [fraudulent users of an online store](https://docs.google.com/presentation/d/1UdI5NY-mlHyseiRVbpTLyvbrHxY8RciHp5Vc-ZLrwmU/edit#slide=id.p), identifying [bots in an online auction](https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot/forums/t/14628/share-your-secret-sauce), predicting who will [subscribe to the next season of an orchestra](http://blog.kaggle.com/2015/01/05/kaggle-inclass-stanfords-getting-a-handel-on-data-science-winners-report/), and evaluating the [quality of e-commerce search engine results](http://blog.kaggle.com/2015/07/22/crowdflower-winners-interview-3rd-place-team-quartet/).

-----

### Class 17: Decision Trees
* Decision trees ([notebook](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/17_decision_trees.ipynb), [notebook code](code/17_decision_trees_nb.py))

**Homework:**
* You will be assigned to review the project drafts of two of your peers. You have until next Monday to provide them with feedback, according to the [peer review guidelines](project/peer_review.md).
* Read the "Wisdom of the crowds" section from MLWave's post on [Human Ensemble Learning](http://mlwave.com/human-ensemble-learning/).
* **Optional:** Read the abstract from [Do We Need Hundreds of Classifiers to Solve Real World Classification Problems?](http://jmlr.csail.mit.edu/papers/volume15/delgado14a/delgado14a.pdf), as well as Kaggle CTO Ben Hamner's [comment](https://news.ycombinator.com/item?id=8719723) about the paper, paying attention to the mentions of "Random Forests".

**Resources:**
* scikit-learn's documentation on [decision trees](http://scikit-learn.org/stable/modules/tree.html) includes a nice overview of trees as well as tips for proper usage.
* For a more thorough introduction to decision trees, read section 4.3 (23 pages) of [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php). (Chapter 4 is available as a free download.)
* This paper, [The Science of Singing Along](http://www.doc.gold.ac.uk/~mas03dm/papers/PawleyMullensiefen_Singalong_2012.pdf), contains a neat regression tree for predicting the percentage of an audience at a music venue that will sing along to a pop song.
* If you want to go deep into the different decision tree algorithms, this slide deck contains [A Brief History of Classification and Regression Trees](https://drive.google.com/file/d/0B-BKohKl-jUYQ3RpMEF0OGRUU3RHVGpHY203NFd3Z19Nc1ZF/view).

**Installing GraphViz (optional):**
* Mac: [Download and install PKG file](http://www.graphviz.org/Download_macos.php)
* Windows: [Download and install MSI file](http://www.graphviz.org/Download_windows.php), and then add GraphViz to your path:
    * Go to Control Panel, System, Advanced System Settings, Environment Variables
    * Under system variables, edit "Path" to include the path to the "bin" folder, such as: `C:\Program Files (x86)\Graphviz2.38\bin`

-----

### Class 18: Ensembling
* Finish decision trees lesson
* Ensembling ([notebook](http://nbviewer.ipython.org/github/justmarkham/DAT7/blob/master/notebooks/18_ensembling.ipynb), [notebook code](code/18_ensembling_nb.py))

**Resources:**
* scikit-learn's documentation on [ensemble methods](http://scikit-learn.org/stable/modules/ensemble.html) covers both "averaging methods" (such as bagging and Random Forests) as well as "boosting methods" (such as AdaBoost and Gradient Tree Boosting).
* For an intuitive explanation of Random Forests, read Edwin Chen's answer to [How do random forests work in layman's terms?](http://www.quora.com/Random-Forests/How-do-random-forests-work-in-laymans-terms/answer/Edwin-Chen-1)
* MLWave's [Kaggle Ensembling Guide](http://mlwave.com/kaggle-ensembling-guide/) is very thorough and shows the many different ways that ensembling can take place.
* Browse the excellent [solution paper](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/ChenglongChen/Kaggle_CrowdFlower/master/Doc/Kaggle_CrowdFlower_ChenglongChen.pdf) from the winner of Kaggle's [CrowdFlower competition](https://www.kaggle.com/c/crowdflower-search-relevance) for an example of the work and insight required to win a Kaggle competition.
* [Interpretable vs Powerful Predictive Models: Why We Need Them Both](https://medium.com/@chris_bour/interpretable-vs-powerful-predictive-models-why-we-need-them-both-990340074979) is a short post on how the tactics useful in a Kaggle competition are not always useful in the real world.

-----

### Class 19: Advanced scikit-learn and Clustering
* Advanced scikit-learn ([code](code/19_advanced_sklearn.py))
    * [GridSearchCV](http://scikit-learn.org/stable/modules/grid_search.html): searching for optimal parameters ([exercise](code/19_grid_exercise.py))
    * [StandardScaler](http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html): standardization of features
    * [Pipeline](http://scikit-learn.org/stable/modules/pipeline.html): chaining steps
* Clustering ([slides](slides/19_clustering.pdf), [code](code/19_clustering.py))
    * K-means: [visualization](http://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
    * DBSCAN: [visualization](http://www.naftaliharris.com/blog/visualizing-dbscan-clustering/)

**Homework:**
* **Optional:** Read this classic paper, which may help you to connect many of the topics we have studied throughout the course: [A Few Useful Things to Know about Machine Learning](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf).

**scikit-learn Resources:**
* For a recap of today's lesson on GridSearchCV, plus a comparison with RandomizedSearchCV, watch [How to find the best model parameters in scikit-learn](https://www.youtube.com/watch?v=Gol_qOgRqfA&list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A&index=8) (28 minutes) or read through the [companion notebook](http://nbviewer.ipython.org/github/justmarkham/scikit-learn-videos/blob/master/08_grid_search.ipynb).
* Here is a longer example of [feature scaling](http://nbviewer.ipython.org/github/rasbt/pattern_classification/blob/master/preprocessing/about_standardization_normalization.ipynb) in scikit-learn, with additional discussion of the types of scaling you can use.
* [Practical Data Science in Python](http://radimrehurek.com/data_science_python/) is a long and well-written notebook that includes the use of scikit-learn's Pipeline.
* scikit-learn has an incredibly active [mailing list](https://www.mail-archive.com/scikit-learn-general@lists.sourceforge.net/index.html) that is often much more useful than Stack Overflow for researching a particular function.

**Clustering Resources:**
* scikit-learn's documentation on [clustering](http://scikit-learn.org/stable/modules/clustering.html) compares many different types of clustering.
* For a very thorough introduction to clustering, read chapter 8 (69 pages) of [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php) (available as a free download), or browse through the chapter 8 slides.
* An Introduction to Statistical Learning has useful videos on [K-means clustering](https://www.youtube.com/watch?v=aIybuNt9ps4&list=PL5-da3qGB5IBC-MneTc9oBZz0C6kNJ-f2) (17 minutes) and [hierarchical clustering](https://www.youtube.com/watch?v=Tuuc9Y06tAc&list=PL5-da3qGB5IBC-MneTc9oBZz0C6kNJ-f2) (15 minutes).
* Fun examples of clustering: [A Statistical Analysis of the Work of Bob Ross](http://fivethirtyeight.com/features/a-statistical-analysis-of-the-work-of-bob-ross/) (with [data and Python code](https://github.com/fivethirtyeight/data/tree/master/bob-ross)), [How a Math Genius Hacked OkCupid to Find True Love](http://www.wired.com/2014/01/how-to-hack-okcupid/all/), and [characteristics of your zip code](http://www.esri.com/landing-pages/tapestry/).

-----

### Class 20: Course Review
* [Data science review](https://docs.google.com/document/d/1pwSGwz5lDeQMNheTOacKptusW2Q6gQ5uTiu5EkKicmk/edit?usp=sharing)
* [Comparing supervised learning algorithms](https://docs.google.com/spreadsheets/d/1tne8UpZwJkvHy7C7NPxjCsF5mFm5mENP2AQ9OS7w3no/edit?usp=sharing) ([related blog post](http://www.dataschool.io/comparing-supervised-learning-algorithms/))

**Homework:**
* Your final project is due next week!

**Resources:**
* scikit-learn's [machine learning map](http://scikit-learn.org/stable/tutorial/machine_learning_map/) may help you to choose the "best" model for your task.
* [Choosing a Machine Learning Classifier](http://blog.echen.me/2011/04/27/choosing-a-machine-learning-classifier/) provides a short and highly readable comparison of several classification models, whereas [Supervised learning superstitions cheat sheet](http://ryancompton.net/assets/ml_cheat_sheet/supervised_learning.html) is a much more thorough comparison (with links to lots of useful resources).
* [Machine Learning Done Wrong](http://ml.posthaven.com/machine-learning-done-wrong), [Clever Methods of Overfitting](http://hunch.net/?p=22), and [Common Pitfalls in Machine Learning](http://danielnee.com/?p=155) all offer thoughtful advice on how to avoid common mistakes in machine learning.
* [Practical machine learning tricks from the KDD 2011 best industry paper](http://blog.david-andrzejewski.com/machine-learning/practical-machine-learning-tricks-from-the-kdd-2011-best-industry-paper/) includes slightly more advanced advice than the resources above.
* [An Empirical Comparison of Supervised Learning Algorithms](http://www.cs.cornell.edu/~caruana/ctp/ct.papers/caruana.icml06.pdf) is a readable research paper from 2006.

-----

### Classes 21 and 22: Final Project Presentation
* Project presentations!
* [What's next?](other/advice.md)

-----

## Bonus Resources

### Databases and SQL
* This [GA slide deck](https://github.com/justmarkham/DAT5/blob/master/slides/20_sql.pdf) provides a brief introduction to databases and SQL. The [Python script](https://github.com/justmarkham/DAT5/blob/master/code/20_sql.py) from that lesson demonstrates basic SQL queries, as well as how to connect to a SQLite database from Python and how to query it using Pandas.
* The repository for this [SQL Bootcamp](https://github.com/brandonmburroughs/sql_bootcamp) contains an extremely well-commented SQL script that is suitable for walking through on your own.
* This [GA notebook](http://nbviewer.ipython.org/github/podopie/DAT18NYC/blob/master/classes/17-relational_databases.ipynb) provides a shorter introduction to databases and SQL that helpfully contrasts SQL queries with Pandas syntax.
* [SQLZOO](http://sqlzoo.net/wiki/SQL_Tutorial), [Mode Analytics](http://sqlschool.modeanalytics.com/), and [Code School](http://campus.codeschool.com/courses/try-sql/contents) all have online beginner SQL tutorials that look promising. Code School also offers an [advanced tutorial](https://www.codeschool.com/courses/the-sequel-to-sql/), though it's not free.
* [w3schools](http://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) has a sample database that allows you to practice SQL from your browser. Similarly, Kaggle allows you to query a large SQLite database of [Reddit Comments](https://www.kaggle.com/c/reddit-comments-may-2015/data) using their online "Scripts" application.
* [What Every Data Scientist Needs to Know about SQL](http://joshualande.com/data-science-sql/) is a brief series of posts about SQL basics, and [Introduction to SQL for Data Scientists](http://bensresearch.com/downloads/SQL.pdf) is a paper with similar goals.
* [10 Easy Steps to a Complete Understanding of SQL](http://tech.pro/tutorial/1555/10-easy-steps-to-a-complete-understanding-of-sql) is a good article for those who have some SQL experience and want to understand it at a deeper level.
* SQLite's article on [Query Planning](http://www.sqlite.org/queryplanner.html) explains how SQL queries "work".
* [A Comparison Of Relational Database Management Systems](https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems) gives the pros and cons of SQLite, MySQL, and PostgreSQL.
* If you want to go deeper into databases and SQL, Stanford has a well-respected series of [14 mini-courses](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about).
* [Blaze](http://blaze.pydata.org/en/latest/) is a Python package enabling you to use Pandas-like syntax to query data living in a variety of data storage systems.

### Tidy Data
* [Good Data Management Practices for Data Analysis](https://www.prometheusresearch.com/good-data-management-practices-for-data-analysis-tidy-data-part-2/) briefly summarizes the principles of "tidy data".
* [Hadley Wickham's paper](http://www.jstatsoft.org/v59/i10/paper) explains tidy data in detail and includes lots of good examples.
* Example of a tidy dataset: [Bob Ross](https://github.com/fivethirtyeight/data/blob/master/bob-ross/elements-by-episode.csv)
* Examples of untidy datasets: [NFL ticket prices](https://github.com/fivethirtyeight/data/blob/master/nfl-ticket-prices/2014-average-ticket-price.csv), [airline safety](https://github.com/fivethirtyeight/data/blob/master/airline-safety/airline-safety.csv), [Jets ticket prices](https://github.com/fivethirtyeight/data/blob/master/nfl-ticket-prices/jets-buyer.csv), [Chipotle orders](https://github.com/TheUpshot/chipotle/blob/master/orders.tsv)
* If your co-workers tend to create spreadsheets that are [unreadable by computers](https://bosker.wordpress.com/2014/12/05/the-government-statistical-services-terrible-spreadsheet-advice/), they may benefit from reading these [tips for releasing data in spreadsheets](http://www.clean-sheet.org/). (There are some additional suggestions in this [answer](http://stats.stackexchange.com/questions/83614/best-practices-for-creating-tidy-data/83711#83711) from Cross Validated.)

### Regular Expressions ("Regex")
* [RegexOne](http://regexone.com/) is an interactive tutorial for learning the basics of regular expressions.
* Google's Python Class includes an excellent [introductory lesson](https://developers.google.com/edu/python/regular-expressions) on regular expressions (which also has an associated [video](https://www.youtube.com/watch?v=kWyoYtvJpe4&index=4&list=PL5-da3qGB5IA5NwDxcEJ5dvt8F9OQP7q5)).
* Python for Informatics has a nice [chapter](http://www.pythonlearn.com/html-270/book012.html) on regular expressions. (If you want to run the examples, you'll need to download [mbox.txt](http://www.py4inf.com/code/mbox.txt) and [mbox-short.txt](http://www.py4inf.com/code/mbox-short.txt).)
* My [reference guide](https://github.com/justmarkham/DAT5/blob/master/code/19_regex_reference.py) to regular expressions includes lots of short explanations and simple examples.
* [regex101](https://regex101.com/#python) is an online tool for testing your regular expressions in real time.
* If you want to go really deep with regular expressions, [RexEgg](http://www.rexegg.com/) includes endless articles and tutorials.
* [Exploring Expressions of Emotions in GitHub Commit Messages](http://geeksta.net/geeklog/exploring-expressions-emotions-github-commit-messages/) is a fun example of how regular expressions can be used for data analysis, and [Emojineering](http://instagram-engineering.tumblr.com/post/118304328152/emojineering-part-2-implementing-hashtag-emoji) explains how Instagram uses regular expressions to detect emoji in hashtags.

### Regularization
* This [GA notebook](http://nbviewer.ipython.org/github/justmarkham/DAT5/blob/master/notebooks/18_regularization.ipynb) provides an introduction to regularization for linear models. The [Python script](https://github.com/justmarkham/DAT5/blob/master/code/18_regularization.py) from that lesson demonstrates ridge regression, lasso regression, and regularized logistic regression.
* This [notebook](http://nbviewer.ipython.org/github/luispedro/PenalizedRegression/blob/master/PenalizedRegression.ipynb) from chapter 7 of [Building Machine Learning Systems with Python](https://www.packtpub.com/big-data-and-business-intelligence/building-machine-learning-systems-python) has a nice long example of regularized linear regression.
* The scikit-learn user guide for [Generalized Linear Models](http://scikit-learn.org/stable/modules/linear_model.html) explains the different variations of regularization.
* Section 6.2 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (14 pages) introduces both ridge regression and lasso regression. Or, watch the related videos on [ridge regression](https://www.youtube.com/watch?v=cSKzqb0EKS0&list=PL5-da3qGB5IB-Xdpj_uXJpLGiRfv9UVXI&index=6) (13 minutes) and [lasso regression](https://www.youtube.com/watch?v=A5I1G1MfUmA&index=7&list=PL5-da3qGB5IB-Xdpj_uXJpLGiRfv9UVXI) (15 minutes).
* Caltech's Learning From Data course has a great video introducing [regularization](http://work.caltech.edu/library/121.html) (8 minutes) that builds upon their video about the [bias-variance tradeoff](http://work.caltech.edu/library/081.html).
* For a math-ier explanation of regularization, watch the last four videos (30 minutes) from week 3 of Andrew Ng's [machine learning course](https://www.coursera.org/learn/machine-learning/home/info), or read the [related lecture notes](http://www.holehouse.org/mlclass/07_Regularization.html) compiled by a student.
* There are some special considerations when using dummy encoding for categorical features with a regularized model. This [Cross Validated Q&A](https://stats.stackexchange.com/questions/69568/whether-to-rescale-indicator-binary-dummy-predictors-for-lasso) debates whether the dummy variables should be standardized (along with the rest of the features), and a comment on this [blog post](http://appliedpredictivemodeling.com/blog/2013/10/23/the-basics-of-encoding-categorical-data-for-predictive-models) recommends that the baseline level should not be dropped.

### Recommendation Systems
* This [GA slide deck](https://github.com/justmarkham/DAT4/blob/master/slides/18_recommendation_engines.pdf) provides a brief introduction to recommendation systems, and the [Python script](https://github.com/justmarkham/DAT4/blob/master/code/18_recommenders_soutions.py) from that lesson demonstrates how to build a simple recommender.
* Chapter 9 of [Mining of Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/bookL.pdf) (36 pages) is a more thorough introduction to recommendation systems.
* Chapters 2 through 4 of [A Programmer's Guide to Data Mining](http://guidetodatamining.com/) (165 pages) provides a friendlier introduction, with lots of Python code and exercises.
* The Netflix Prize was the famous competition for improving Netflix's recommendation system by 10%. Here are some useful articles about the Netflix Prize:
    * [Netflix Recommendations: Beyond the 5 stars](http://techblog.netflix.com/2012/04/netflix-recommendations-beyond-5-stars.html): Two posts from the Netflix blog summarizing the competition and their recommendation system
    * [Winning the Netflix Prize: A Summary](http://blog.echen.me/2011/10/24/winning-the-netflix-prize-a-summary/): Overview of the models and techniques that went into the winning solution
    * [A Perspective on the Netflix Prize](http://www2.research.att.com/~volinsky/papers/chance.pdf): A summary of the competition by the winning team
* This [paper](http://www.cs.umd.edu/~samir/498/Amazon-Recommendations.pdf) summarizes how Amazon.com's recommendation system works, and this [Stack Overflow Q&A](http://stackoverflow.com/questions/2323768/how-does-the-amazon-recommendation-feature-work) has some additional thoughts.
* [Facebook](https://code.facebook.com/posts/861999383875667/recommending-items-to-more-than-a-billion-people/) and [Etsy](https://codeascraft.com/2014/11/17/personalized-recommendations-at-etsy/) have blog posts about how their recommendation systems work.
* [The Global Network of Discovery](http://www.gnod.com/) provides some neat recommenders for music, authors, and movies.
* [The People Inside Your Machine](http://www.npr.org/blogs/money/2015/01/30/382657657/episode-600-the-people-inside-your-machine) (23 minutes) is a Planet Money podcast episode about how Amazon Mechanical Turks can assist with recommendation engines (and machine learning in general).
* Coursera has a [course](https://www.coursera.org/learn/recommender-systems) on recommendation systems, if you want to go even deeper into the material.
