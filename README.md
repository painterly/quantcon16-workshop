
## Intro to Python for Data Analysis Workshop

### Setup Instructions

#### Option 1
**If you don't have Python3 or Pip installed:**
* Install Anaconda3 from conda.pydata.org/docs/install/full.html

** Run the following commands:**
* conda update anaconda
* conda create -n workshop jupyter numpy pandas matplotlib seaborn
* source activate workshop


#### Option 2
**If you do have or want to install Python3 and Pip:**
* Install Python from https://www.python.org/downloads/ 

** Run the following commands on the command line:**
* pip3 install jupyter numpy pandas matplotlib seaborn
* (if any issues with dependencies then go with Option 1)


#### Option 3
**If you want to use a Docker container(advanced):**
* docker pull jupyter/scipy-notebook

** Run the following commands on the command line:**
* docker run -t -i -p 8888:8888 jupyter/scipy-notebook /bin/bash
* (presumes experience using Docker)


### Resources for break out sessions
* Pandas Documentation 
  * http://pandas.pydata.org
* Python Documentation
  * http://docs.python.org/3/
* Visualization links
  * http://stanford.edu/~mwaskom/software/seaborn/
* Stack Overflow
  * http://stackoverflow.com
* Help functions and docstrings available in the notebook



### My learning resources
* Practical Data Analysis with Python 
  * http://leanpub.com/analyticshandbook
* Free screencasts on Python and Numpy basics
  * http://youtube.com/channel/UCAteIywHWq-WhiXIj_1vS3w
* Intro Python slides
  * http://slides.com/practicaldatascience


