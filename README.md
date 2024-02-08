# Urban Informatics and Data Visualization (CYPLAN255) 
Course repo for material related to CYPLAN 255 at UC Berkeley, Spring 2024

## Getting started
- Please fill out the [Pre-Semester Survey](https://forms.gle/2x8Bw913GpxukYwFA)!
- Check out the [Wiki](https://github.com/mxndrwgrdnr/UCB_CYPLAN255_2024/wiki)!
- Skip to [class schedule](https://github.com/mxndrwgrdnr/UCB_CYPLAN255_2024#topics--course-schedule)

## Syllabus

CYPLAN255: Urban Informatics and Data Visualization <br>
Department of City and Regional Planning, UC Berkeley<br>
Spring 2024

| | |
|:--|:--|
|**Instructor**| Max Gardner / [magardner@berkeley.edu](mailto:magardner@berkeley.edu) <br> Office hours (Zoom): Mon/Tues 5-6 pm -- sign-up [here](https://calendly.com/maxgardner/office-hours-individual)|
| **GSI**| Meiqing Li / [meiqing@berkeley.edu](mailto:irenef@berkeley.edu) <br> Office hours (Zoom): Thurs 7:30-8:30 pm -- sign-up [here](https://calendly.com/meiqingli/office-hour) <br> Office hours (IRL): Fri 12-1pm, BW Rm 222|
|**Details**| Meeting times: Mon/Wed 6-7:30 pm <br> Meeting location: [Zoom](https://berkeley.zoom.us/j/93655092809) <br> Course website: [https://bcourses.berkeley.edu/courses/1532651](https://bcourses.berkeley.edu/courses/1532651) <br> Course GitHub repository: [https://github.com/mxndrwgrdnr/UCB_CYPLAN255_2024](https://github.com/mxndrwgrdnr/UCB_CYPLAN255_2024) <br> Prerequisites: CP201A, CP204C, or equivalent experience <br> Grading: out of 100 pts – attendance (10%) / assignments (15%) / project (75%) <br> Letter grade scale: 0-59% F, 60-69% D, 70-79% C, 80-89% B, 90-100% A|

### Overview

The goal of this course is to train students to analyze urban data, derive insights, and create effective visualizations using open source software tools and public data. The course will first introduce the fundamentals of programming in Python before moving on to a survey of data analysis/visualization tools and technologies. Sessions will include lectures and practice exercises. Assignments will reinforce the skills and topics being presented. A final project will provide an opportunity for students to use these skills to complete an end-to-end data analysis of their own design, the results of which will be published on GitHub and presented in class.

This is a &quot;hands-on&quot; course. It requires some tolerance for experimentation, self-directed trial and error, and an interest in learning to write code. If you are willing to roll up your sleeves and embrace some uncertainty, you&#39;ll learn the fundamentals of urban data analysis and visualization, and might discover an entirely new lens through which to study, plan, and design neighborhoods, cities, and regions.

### Course Materials and Attendance

Attendance will be recorded on Zoom. Students are granted two excused absences over the course of semester without affecting their attendance grade. Qualifying exceptions will be handled on a case-by-case basis.

All required readings will be provided via bCourses or hyperlinks on this electronic syllabus. Lecture slides, example code, and demos/exercises will all be made available via GitHub.

We&#39;ll write code in Jupyter notebooks using the Anaconda Python distribution plus some additional software libraries. In some cases you may want to use a Berkeley service called [DataHub](https://datahub.berkeley.edu/) instead of your own computer – but in general we encourage you to get comfortable installing Python and Python tools on your own computer. You&#39;ll get far more comfortable with it that way, and know that whatever you learn, and whatever you install, you can take with you when the class is over. We will use only open source, free software in this course. You&#39;ll be surprised how far you can go with it.

You should plan to bring a laptop\*\* to all class sessions.

\*\*NOTE TO WINDOWS USERS: Most exercises and lectures will be OS-agnostic, but command-line tools will be demonstrated in a Unix-like terminal. Windows users can use the Windows command prompt if they choose, but instructor support will be limited. Instead, I recommend installing one of the following to gain access to a Unix-like shell: [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/about), [Cygwin](https://www.cygwin.com/), [Git Bash](https://gitforwindows.org/), or [PyCharm](https://www.jetbrains.com/pycharm/download/).

### Assignments (15 pts)

Students will develop skills gradually through assignments paced over the semester. These will typically involve writing some code and documenting it, using Jupyter Notebooks that can be shared and interactively run inside a web browser, and providing a writeup discussing the assignment and its results.

Assignments will be posted on the course GitHub repository, and students will need to pull them down from there. Assignments will generally be due one week from the day they are assigned, by 11:59pm PST. Students will submit their completed assignments by opening a pull request on the course repo.

Assignments are designed to build a degree of mastery of skills and will be used as a means of ensuring that students are keeping up with the material and not falling behind. All assignments will be marked down 10% for each day late, so please submit on time.

### Readings and Exercises (ungraded)

This course has readings associated with nearly every class meeting. These are _suggested_ readings, unless otherwise specified. You will not be quizzed on them, and they may or may not be referenced in class. They are, however, **strongly recommended**. They have been thoughtfully compiled over the many years this course has been taught, and are designed to help you get the most of this course and make your final projects a success.

In addition to the readings, the Course Schedule (see below) specifies several other **exercises** which, unless explicitly stated, will not be collected. They will, however, be used for the following: 1) to facilitate discussion/break-out groups in class; 2) to inspire final project ideas; and 3) to ensure that you make steady progress on your final projects throughout the course of the semester. In some cases there will be class time designated for working on these ungraded exercises, but not always. It is in your own best interest, and that of your fellow students, that you keep up with them.

### Final Projects (75 pts)

Final projects will require harnessing the skills practiced in the exercises and developing a more independent work plan to accomplish an analysis of data. More details will be provided later in the semester.

Project components and due dates:

1. Project proposal + initial analysis (10 pts)
   - Due Sunday, Mar 10
2. Final presentation (20 pts)
   - Slides, etc. presented during the last week of class.
3. github.io project page (45 pts)
   - Due Monday, May 6 (first day of Finals week)

### Self-Reliance, Collaboration, and Academic Integrity

This course requires a lot of experimentation and trial-and-error. Google and [StackOverflow](https://stackoverflow.com/) will be your best friends! Google your questions, Google any error messages, and if you can&#39;t find an answer, talk to your classmates, and if you still can&#39;t sort it out, e-mail Max and Irene. When you e-mail us, tell us what you&#39;ve searched and what you&#39;ve discovered, and include screenshots, links, and error messages. 99% of the time, somebody else has encountered the exact issue you are having and has documented the solution.

That being said, you are welcome — in fact, encouraged — to work on the homework exercises and your semester project together with other students. Discussing code is a great way to understand it better, and can make tracking down bugs less frustrating. If you copy an entire substantive piece of code (i.e., several lines or more) from the internet or from another student, we ask that you indicate this in a code comment. Otherwise, we will expect everything you submit to be your own original work. Details of the U.C. Berkeley Academic Honor Code can be found [here](https://teaching.berkeley.edu/berkeley-honor-code).

### Campus Policies and Guidelines

[https://teaching.berkeley.edu/campus-policies](https://teaching.berkeley.edu/campus-policies)

### Accommodations for Students with Disabilities

UC Berkeley is committed to creating a learning environment that meets the needs of its diverse student body. If you anticipate or experience any barriers to learning in this course, please feel welcome to discuss your concerns with me.

If you have a disability, or think you may have a disability, you can work with the Disabled Students&#39; Program (DSP) to request an official accommodation. The Disabled Students&#39; Program (DSP) is the campus office responsible for authorizing disability-related academic accommodations, in cooperation with the students themselves and their instructors. You can find more information about DSP, including contact information and the application process [here](https://dsp.berkeley.edu/). If you have already been approved for accommodations through DSP, please meet with me so we can develop an implementation plan together.

_Students who need academic accommodations or have questions about their accommodations should contact DSP, located at 260 César Chávez Student Center. Students may call 510-642-0518 (voice), 510-642-6376 (TTY), or email dsp@berkelely.edu._

### Department Climate Statement

The Department of City and Regional Planning in the College of Environmental Design is committed to an equitable and inclusive educational environment for all. As students, staff, and faculty, we strive to foster a community in which we celebrate our diversity and affirm the dignity of each person by respecting the identities, perspectives, and experiences of those with whom we work. As a member of the UC Berkeley community, the Department of City and Regional Planning is committed to a safe work environment for all.

The following campus-wide resources are available to assist with this effort:

- [Gender Equity Resource Center](https://campusclimate.berkeley.edu/students/ejce/geneq)
- [Path to Care: Sexual Violence and Sexual Harassment](https://svsh.berkeley.edu/support-resources)
- [Office for the Prevention of Harassment and Discrimination (OPHD)](https://ophd.berkeley.edu/)
- [OPHD info for students, staff, and faculty](https://ophd.berkeley.edu/policies-and-procedures)
- [University Health Services: Counseling and Psychological Services](https://uhs.berkeley.edu/counseling)
- [Centers for Educational Justice and Community Engagement](https://campusclimate.berkeley.edu/students/ejce)

### Reading Material and Web Resources

The following books and websites may be helpful resources, and we will draw material from many of them during the semester. (All readings assigned for class will be available online or as PDFs in bCourses.) Each piece of software we&#39;ll use also has official documentation online.

- **Adhikari, Ani and John DeNero, Computational and Inferential Thinking, 2019**([https://inferentialthinking.com](https://inferentialthinking.com/))
  - Online textbook developed for Berkeley&#39;s Foundations of Data Science class.

- **Downey, Allen, Think Python, 2nd Edition, O&#39;Reilly Media, 2015**([https://learning-python.com/about-lp5e.html](https://learning-python.com/about-lp5e.html))
  - Introduction to programming using Python. All the material is online.

- **Foster, Ian, et al., Big Data and Social Science, CRC Press, 2017**
  - A practical guide to gathering data and working with it in various ways.

- **Lutz, Mark, Learning Python, 5th Edition, O&#39;Reilly Media, 2013**([https://learning-python.com/about-lp5e.html](https://learning-python.com/about-lp5e.html))
  - Much more depth than you need for this class, but a great reference.

- **McKinney, Wes, Python for Data Analysis, 2nd Edition, O&#39;Reilly Media, 2017**
  - More depth about Pandas than Python Data Science Handbook, but less readable.

- **Pilgrim, Mark, Dive into Python 3, Apress, 2009** ([https://diveintopython3.net](https://diveintopython3.net/))
  - Nice tutorials and reference for aspects of core Python syntax and programming concepts, but missing some topics that are in Think Python. All the material is online.

- **VanderPlas, Jake, Python Data Science Handbook, O&#39;Reilly Media, 2016**([https://jakevdp.github.io/PythonDataScienceHandbook](https://jakevdp.github.io/PythonDataScienceHandbook))
  - Excellent – working with data, making graphs and charts, machine learning. All the material is online.

- **Real Python** (https://realpython.com)
  — Great Python tutorials on numerous topics.

- **Rey, Sergio, et al., Geographic Data Science with Python, 2020** ([https://geographicdata.science/book/intro.html](https://geographicdata.science/book/intro.html))
  - Great resource for geospatial data analysis in Python from the creators of PySAL.

- **Software Carpentry** (https://software-carpentry.org/lessons)
  - Tutorials about scientific computing.

- **Stack Overflow** (https://stackoverflow.com)
  — Best website for user-contributed coding Q&amp;As.

### Topics + Course Schedule

The topics covered by this course are organized into the following seven (7) modules:

1. [Fundamentals of Programming](https://github.com/mxndrwgrdnr/UCB_CYPLAN255_2024#module-1-fundamentals-of-programming)
2. [Intro to Data Analysis in Python](https://github.com/mxndrwgrdnr/UCB_CYPLAN255_2024#module-2-intro-to-data-analysis-in-python)
3. [Intro to Data Visualization](https://github.com/mxndrwgrdnr/UCB_CYPLAN255_2024#module-3-intro-to-data-visualization)
4. [APIs + Open Data](https://github.com/mxndrwgrdnr/UCB_CYPLAN255_2024#module-4-open-data-and-apis)
5. [Working with Geospatial Data](https://github.com/mxndrwgrdnr/UCB_CYPLAN255_2024#module-5-working-with-geospatial-data)
6. [Visualizing Spatial Data](https://github.com/mxndrwgrdnr/UCB_CYPLAN255_2024#module-6-visualizing-geospatial-data)
7. [Statistical Analysis + Machine Learning](https://github.com/mxndrwgrdnr/UCB_CYPLAN255_2024#module-7-statistical-analysis--machine-learning)

----

#### MODULE 1: FUNDAMENTALS OF PROGRAMMING

- **Weds, Jan 17 -- Course Introduction:** Overview of the course, expectations, prerequisites, learning objectives, assignments and projects.
  - Exercises
    - Install the Anaconda distribution of Python on your computer, and verify that it is working. Find your download [here](https://www.anaconda.com/products/individual).
    - Create a personal GitHub account using your Berkeley e-mail address.
    - Via bCourses, submit links to three (3) examples of interesting public/open datasets that you think you or your fellow students might be interested in exploring in the context of this class. In 2-3 sentences, describe their relevance to topics in transportation, housing, land use, urban design, etc. Show us something we haven&#39;t seen before – the American Community Survey doesn&#39;t count!
  - Readings
    - Why Python:
      - [http://lorenabarba.com/blog/why-i-push-for-python/](http://lorenabarba.com/blog/why-i-push-for-python/)
      - [https://www.codefellows.org/blog/5-reasons-why-python-is-powerful-enough-for-google](https://www.codefellows.org/blog/5-reasons-why-python-is-powerful-enough-for-google)
    - Chapter 1 of [Think Python](https://greenteapress.com/wp/think-python-2e/)
    - Wilson et al. &quot;Best practices for scientific computing,&quot; PLOS Biology, 2014. [https://doi.org/10.1371/journal.pbio.1001745](https://doi.org/10.1371/journal.pbio.1001745)

- **Mon, Jan 22 -- Intro to the Command-line:** Using a command-line interpreter; common syntax, programs, and arguments; accessing and navigating the file system; Python interpreters; conda environments; starting/stopping a Jupyter server; using Git; text editors

  - Exercises
    - Fork the CYPLAN255 GitHub repo and push your first commit.

  - Readings
    - Command-line guides for [Windows](https://www.cs.princeton.edu/courses/archive/spr05/cos126/cmd-prompt.html) or [Unix-like](https://www.davidbaumgold.com/tutorials/command-line/) (MacOS/Linux)
    - Sections 1.1 and 1.3 of [Pro Git](https://git-scm.com/book/en/v2) by Chacon and Straub
    - [https://docs.github.com/en/get-started/using-git/about-git](https://docs.github.com/en/get-started/using-git/about-git)

- **Weds, Jan 24 -- Git and GitHub:** Principles of distributed version control; repositories; commits; branches; forks; making a GitHub pages website

  - Exercises
    - Create your own github.io website by following [this](http://data94.org/resources/assets/homework/hw09/) helpful tutorial from the Data89 class at Cal. For advanced users, take it one step further with a slightly more advanced version [here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll).
       - _NOTE: although this is only listed as an "exercise" and not an "assignment", your final project will be submitted as a GitHub Pages website, so it would be wise to get started on this sooner than later._

  - Readings
    - [https://docs.github.com/en/get-started/using-git/about-git](https://docs.github.com/en/get-started/using-git/about-git)

- **Mon, Jan 29 -- Python at the Command-line** Anaconda distro; Python vs. IPython vs. Jupyter; virtual environments; intro to the Jupyter Notebook
  - Assignments
    - Assignment 1 released (due Sun, Feb 11) 
 
  - Exercises
    - Re-read and work your way through "notebooks/lecture_03_intro_python_jupyter.ipynb"
    - Continue to work your way through the GitHub Pages website tutorial.

  - Readings
    - Chapter 3 of [Python for Data Analysis](https://github.com/wesm/pydata-book)
    - Chapters 2, 4 of [Dive Into Python 3](http://www.diveintopython3.net/)
    - Chapters 8, 10, 11, 12 of [Think Python](http://www.greenteapress.com/thinkpython/)

- **Weds, Jan 31 -- The Python Standard Library** Variables, expressions, and assignment; built-in functions and data types; the `math` module; working with strings and lists and dicts.
  - Readings
     - The Python Standard Library from the [Official Python docs](https://docs.python.org/3/library/index.html)
     - Chained assignment vs. copying from the Towards Data Science [blog](https://towardsdatascience.com/assignment-shallow-or-deep-a-story-about-pythons-memory-management-b8fad87bfa6c)
     - Jean Mark Gawron's [Intro to Python](https://gawron.sdsu.edu/python_for_ss/course_core/book_draft/Python_introduction/Python_introduction.html)

----

#### MODULE 2: INTRO TO DATA ANALYSIS IN PYTHON

- **Mon, Feb 5 -- Programming Logic:** Procedural programming; control flow in Python (conditional logic, loops, functions)
  - Readings
    - Chapters 2, 3, 5-7 of [Think Python](http://www.greenteapress.com/thinkpython/)
    - Chapters 1, 7 of [Dive Into Python 3](http://www.diveintopython3.net/)

- **Wed, Feb 7 -- Object-oriented Programming:** Modules, classes, methods, and functions; namespaces and scopes; `lambda` functions and `map()` for iteration
  - Readings
    - Official Python docs on [Classes](https://docs.python.org/3/tutorial/classes.html)
  - Assignments
    - Assignment 2 released (due Tues, Feb 13)

- **Mon, Feb 12 -- Data Analysis in Python:** NumPy arrays and matrices; Pandas Series and DataFrames; loading, displaying and exporting data; descriptive statistics; indexing and filtering

  - Readings
    - Chapters 4, 5, and 6 of Wes McKinney&#39;s [Python for Data Analysis](https://github.com/wesm/pydata-book)

- **Wed, Feb 14 💘 -- More Pandas:** Vectorized operations; merge, join, concatenate; group by and aggregations; cleaning and imputing missing data

  - Readings
    - Chapter 7 in [Python for Data Analysis](https://github.com/wesm/pydata-book)
  - Exercises
    - Spend 2-3 hours working through notebooks 7 and 8 on your own

-----

#### MODULE 3: INTRO TO DATA VISUALIZATION

- **Mon, Feb 19** _NO CLASS_ _(President&#39;s Day)_
  - Exercises
    - Spend 2-3 hours working through notebooks 7 and 8 on your own
  - Assignments
    - Assignment 3 released (due Tues, Feb 27)

- **Wed, Feb 21 -- Data Visualization Pt. I:** Data viz. for good and evil; use Matplotlib and Seaborn to create static images; dimensionality of data; continuous vs. categorical data; univariate distributions

  - Exercises
    - Find three (3) examples of interesting data visualizations and describe in 2-3 sentences what makes each of them good, bad, or misleading. Be prepared to talk about them in class.

  - Readings
    - Chapter 1 of _Envisioning Information_ (Tufte, 1990)
    - Chapter 9 in [Python for Data Analysis](https://github.com/wesm/pydata-book)
    - [Seaborn](https://seaborn.pydata.org/tutorial.html) tutorial/documentation

- **Mon, Feb 26 -- Data Visualization Pt. II:** Interactive plots, widgets, and apps.

  - Readings
    - Interactive Bokeh [tutorials](https://hub.gke2.mybinder.org/user/bokeh-bokeh-notebooks-th9hef96/notebooks/tutorial/00%20-%20Introduction%20and%20Setup.ipynb)
    - [Plotly](https://plotly.com/python/) tutorial/documentation
    - Streamlit [tutorial](https://medium.com/analytics-vidhya/web-application-in-10-minutes-with-streamlit-99685e3350e0)
    - Comparison of Python dashboarding libraries: [link](https://medium.datadriveninvestor.com/streamlit-vs-dash-vs-voil%C3%A0-vs-panel-battle-of-the-python-dashboarding-giants-177c40b9ea57)

-----

#### MODULE 4: OPEN DATA AND APIs

- **Wed, Feb 28 -- Intro to APIs:** What&#39;s in an API; performing queries; authentication; Socrata;
  - Assignments
    - Project proposal assignment (Assignment 4) released (due Sun, Mar 10) 

  - Readings
    - Red Hat guide to APIs: [here](https://www.redhat.com/en/topics/api/what-are-application-programming-interfaces)
    - Read the Socrata [getting started](https://dev.socrata.com/consumers/getting-started.html) page
    - Look over some of the resources that companies and public agencies have put together for third-party software developers:
      - [BART](http://api.bart.gov/docs/overview/index.aspx)
      - [Twitter](https://dev.twitter.com/overview/documentation)
      - [Google Maps](https://developers.google.com/maps/get-started/)
      - [Urban Institute](https://educationdata.urban.org/documentation/)

- **Mon, Mar 4 -- APIs and Beyond:** Geocoding; web scraping; parsing XML

  - Readings
    - [University of Illinois guide to Geocoding](https://guides.library.illinois.edu/Geocoding)

-----

#### MODULE 5: WORKING WITH GEOSPATIAL DATA

- **Wed, Mar 6 -- Intro to Geospatial Data Analysis:** Vector vs. raster; coordinate reference systems and projections; spatial data types and file formats; spatial indexing; common spatial transformations
  - Assignments
    - Keep working on your project proposal analyses.

  - Exercises
    - Get familiar with OpenStreetMap by reading about it [here](https://wiki.osmfoundation.org/wiki/Main_Page), and contribute at least one (1) change to a Humanitarian OpenStreetMap (HOTOSM) project by following the HOTOSM [quickstart guide](https://tasks.hotosm.org/learn/quickstart).

  - Readings
    - Part I of [Geographic Data Science with Python](https://geographicdata.science/book/notebooks/00_toc.html)
    - [https://wiki.osmfoundation.org/wiki/Main\_Page](https://wiki.osmfoundation.org/wiki/Main_Page)
    - [https://tasks.hotosm.org/learn/quickstart](https://tasks.hotosm.org/learn/quickstart)

- **Mon, Mar 11 -- FOSS tools for Geospatial Data Analysis:** Survey of open source tools for manipulating geospatial data from the command-line, a Python session, a browser, or your desktop.

  - Readings
    - [This](https://developmentseed.org/blog/2015-08-27-introduction-to-the-geo-command-line) great blog post from Development Seed (you can try to follow along with the tutorial on your computer but I think some of the links they use are not longer active)
    - [https://www.osgeo.org/about/what-is-open-source/](https://www.osgeo.org/about/what-is-open-source/)
    - [https://macwright.com/2012/10/31/gis-with-python-shapely-fiona.html](https://macwright.com/2012/10/31/gis-with-python-shapely-fiona.html)

- **Wed, Mar 13 -- Raster data, Remote Sensing, and Google Earth Engine:**

  - Guest speaker: Meiqing!

  - Readings
    - TBD


- **Mon, Mar 18 -- Intro to Network Analysis:** Graph theory; GTFS; Python tools for working with networks

  - Readings
    - Boeing, Geoff. &quot;OSMnx: New methods for acquiring, constructing, analyzing, and visualizing complex street networks.&quot; _Computers, Environment and Urban Systems_ 65 (2017): 126-139. [https://doi.org/10.1016/j.compenvurbsys.2017.05.004](https://doi.org/10.1016/j.compenvurbsys.2017.05.004)
    - Blanchard SD, Waddell P. Assessment of Regional Transit Accessibility in the San Francisco Bay Area of California with UrbanAccess. _Transportation Research Record_. 2017;2654(1):45-54. [https://doi.org/10.3141%2F2654-06](https://doi.org/10.3141%2F2654-06)
    - Foti, Fletcher, Paul Waddell, and Dennis Luxen. &quot;A generalized computational framework for accessibility: from the pedestrian to the metropolitan scale.&quot; _Proceedings of the 4th TRB Conference on Innovations in Travel Modeling. Transportation Research Board_. 2012. [http://onlinepubs.trb.org/onlinepubs/conferences/2012/4thITM/Papers-A/0117-000062.pdf](http://onlinepubs.trb.org/onlinepubs/conferences/2012/4thITM/Papers-A/0117-000062.pdf)
    - [https://www.mapzen.com/blog/animating-transitland/](https://www.mapzen.com/blog/animating-transitland/)
    - Li, Yang, and Wei &quot;David&quot; Fan. &quot;Modeling and evaluating public transit equity and accessibility by integrating general transit feed specification data: Case study of the City of Charlotte.&quot; _Journal of Transportation Engineering, Part A: Systems_ 146.10 (2020): 04020112. Available [here](https://ascelibrary.org/doi/pdf/10.1061/JTEPBS.0000426?casa_token=FXHaQKmwO5MAAAAA:u4NJhaPXXdCbBEut0qdg7dd1d3Bahu6ygF83dWSOU2eBih0S3PrYtvEc7F11p-a7SNk7sKwg).

-----

#### MODULE 6: VISUALIZING GEOSPATIAL DATA

- **Wed, Mar 20 -- Effective Communication of Spatial Data:** Types of geospatial visualizations; color theory; common pitfalls of cartographic representation

  - Readings
    - [https://www.nytimes.com/interactive/2020/10/30/opinion/election-results-maps.html](https://www.nytimes.com/interactive/2020/10/30/opinion/election-results-maps.html)
    - [https://ai.googleblog.com/2019/08/turbo-improved-rainbow-colormap-for.html](https://ai.googleblog.com/2019/08/turbo-improved-rainbow-colormap-for.html)
    - Wong, David WS. &quot;The modifiable areal unit problem (MAUP).&quot; _WorldMinds: Geographical perspectives on 100 problems_. Springer, Dordrecht, 2004. 571-575. [https://doi.org/10.1016/B978-008044910-4.00475-2](https://sci-hubtw.hkvisa.net/10.1016/b978-008044910-4.00475-2)

- **Mon, Mar 25 --** _NO CLASS (🏄 Spring Break 🏄)_

- **Wed, Mar 27 --** _NO CLASS (🏄 Spring Break 🏄)_

- **Mon, Apr 1 -- Building Static Maps in Python:** Survey of Python libraries for plotting geospatial data on a map

  - Readings
    - Norwood, Carla; Cumming, Gabriel (2012). Making Maps That Matter: Situating GIS within Community Conversations about Changing Landscapes. Cartographica: The International Journal for Geographic Information and Geovisualization, 47(1), 2–17. [doi:10.3138/carto.47.1.2](https://sci-hubtw.hkvisa.net/10.3138/carto.47.1.2)
    - Chapter [5](https://geographicdata.science/book/notebooks/05_choropleth.html) of Geographic Data Science with Python

- **Wed, Apr 3 -- Building Interactive Maps:** Survey of tools and technology for creating dynamic maps in Python and other open source frameworks

  - Exercises
    - Work through the bonus notebook on visualizing big geo data

  - Readings
    - [http://www.liedman.net/tiled-maps/](http://www.liedman.net/tiled-maps/)
    - [https://www.axismaps.com/guide/what-is-a-web-map](https://www.axismaps.com/guide/what-is-a-web-map)
    - [https://www.axismaps.com/guide/should-a-map-be-interactive](https://www.axismaps.com/guide/should-a-map-be-interactive)
    - [https://mapbrief.com/2017/04/06/few-interact-with-our-interactive-maps-what-can-we-do-about-it/](https://mapbrief.com/2017/04/06/few-interact-with-our-interactive-maps-what-can-we-do-about-it/)
    - [https://blog.mapbox.com/mapping-millions-of-dots-77eead9bd663](https://blog.mapbox.com/mapping-millions-of-dots-77eead9bd663)
    - [https://shaunastbury.com/creating-a-dot-density-map/](https://shaunastbury.com/creating-a-dot-density-map/)
-----

#### MODULE 7: STATISTICAL ANALYSIS + MACHINE LEARNING

- **Mon, Apr 8 -- Causal Inference Methods in Urban Science:** Deep dive into two examples from the recent literature
  - Readings
    - Greenstone, M. & Gallagher, J. _Does Hazardous Waste Matter? Evidence from the Housing Market and the Superfund Program_. No. w11790. National Bureau of Economic Research, 2005. Available [here](https://www.nber.org/system/files/working_papers/w11790/w11790.pdf).
    - Lawrence, D.F. et al. _Stepping towards causation: Do built environments or neighborhood and travel preferences explain physical activity, driving, and obesity?_ Social Science and Medicine, 2007. Available [here](https://www.sciencedirect.com/science/article/abs/pii/S0277953607003139?casa_token=SaY3vv_H_2AAAAAA:uXwwx-tJd2Tp5cR5E89wXPQbtLXvNDudyf8mI00mzt_op2MbIJRc5MXjApn7-KCZnbHgsMUq)
    - Krizek, Kevin. _Residential Relocation and Changes in Urban Travel: Does Neighborhood-Scale Urban Form Matter?_ Journal of the American Planning Association, 2003. Available [here](https://www.tandfonline.com/doi/pdf/10.1080/01944360308978019?casa_token=F6HCUW4F7DgAAAAA:oOXwalykvP1s5fvkwZBI7BtU8qP0YhE9uygGGYEThdbdBVLWE8m_NqMjSWd26cnYY4vgPpJ_Wz0).
    - Gardner, Max. _The Effect of Rent Control on Eviction Rates: Causal Evidence from San Francisco_. Housing Policy Debate, 2022. Available [here](https://www.tandfonline.com/doi/pdf/10.1080/10511482.2022.2099932?casa_token=cBZenfGAdZYAAAAA:FUNjQkjoFEQTXG2vzk5meFxRyU0_JHBH_fylqOOv9Q6uKdXGGPv8hsmwT0gNbVYT6JIKfAB5zww).

- **Wed, Apr 10 -- Special Topics I: Visualizing Transit Data**
  - Guest speaker: TBD
  
- **Mon, Apr 15 -- Special Topics II: Geospatial Data Activism**
  - Guest speaker: TBD

- **Wed, Apr 17 -- Presentations I**

- **Mon, Apr 22 -- Presentations II** 

- **Wed, Apr 24 -- Presentations III** 

_____

UC Berkeley sits on the territory of xučyun (Huichin), the ancestral and unceded land of the Chochenyo speaking Ohlone people, the successors of the sovereign Verona Band of Alameda County. This land was and continues to be of great importance to the Muwekma Ohlone Tribe and other familial descendants of the Verona Band.

We recognize that every member of the Berkeley community has, and continues to benefit from, the use and occupation of this land, since the institution&#39;s founding in 1868. Consistent with our values of community, inclusion and diversity, we have a responsibility to acknowledge and make visible the university&#39;s relationship to Native peoples.

It is vitally important that we not only recognize the history of the land on which we stand, but also, we recognize that the Muwekma Ohlone people are alive and flourishing members of the Berkeley and broader Bay Area communities today.

Read more on the Centers for Educational Justice &amp; Community Engagement [website.](https://cejce.berkeley.edu/ohloneland)
