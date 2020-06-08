# Student Intervention System - Machine Learning

#### Description

* In the classroom, interventions are activities that you would use to help students become successful in their classwork or decrease negative behavior towards others.
* The greatest benefit of an the intervention approach is that it eliminates a “wait to fail” situation because students get help promptly within the general education setting. As soon as assessment data indicates a problem area for a student or a group of students, interventions are put into place to address these concerns.
* It's important for schools to focus on intensive interventions because it gives an opportunity for the schools to figure out ways to serve their neediest students.

Nowadays, we have access to a vast amount of data regarding to Students and their activities. Logs of student activities, grades, interactions with teachers and fellow students, and more are now captured in real time through various learning management systems.  Especially it is true for online classrooms, which are becoming popular even at the primary and secondary school level. Within all levels of education, there exists a push to help increase the likelihood of student success for their betterment. Graduation rates are often the criteria of choice, and educators seek new ways to predict the success and failure of students early enough to stage effective interventions.

-----

#### Goal
For a school or university to reach a 95% graduation rate by the end of the decade, Is it possible to identify students who need intervention before they perform bad or drop out of school?

Our task is to model the factors that predict how likely a student is to pass their final exam, by constructing a system that leverages supervised learning techniques. We will also have to find the most effective model that uses the least amount of computation costs. In this project we will need to analyze the dataset on students' performance and develop a model that will predict the likelihood that a given student will pass, quantifying whether an intervention is necessary.

-----

#### Dataset file
The dataset used in this project is included as `student data.csv`. The dataset has the following attributes:

- `school` : student's school (binary: "GP" or "MS")
- `sex` : student's sex (binary: "F" - female or "M" - male)
- `age` : student's age (numeric: from 15 to 22)
- `address` : student's home address type (binary: "U" - urban or "R" - rural)
- `famsize` : family size (binary: "LE3" - less or equal to 3 or "GT3" - greater than 3)
- `Pstatus` : parent's cohabitation status (binary: "T" - living together or "A" - apart)
- `Medu` : mother's education (numeric: 0 - none,  1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)
- `Fedu` : father's education (numeric: 0 - none,  1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)
- `Mjob` : mother's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
- `Fjob` : father's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
- `reason` : reason to choose this school (nominal: close to "home", school "reputation", "course" preference or "other")
- `guardian` : student's guardian (nominal: "mother", "father" or "other")
- `traveltime` : home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
- `studytime` : weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
- `failures` : number of past class failures (numeric: n if 1<=n<3, else 4)
- `schoolsup` : extra educational support (binary: yes or no)
- `famsup` : family educational support (binary: yes or no)
- `paid` : extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
- `activities` : extra-curricular activities (binary: yes or no)
- `nursery` : attended nursery school (binary: yes or no)
- `higher` : wants to take higher education (binary: yes or no)
- `internet` : Internet access at home (binary: yes or no)
- `romantic` : with a romantic relationship (binary: yes or no)
- `famrel` : quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
- `freetime` : free time after school (numeric: from 1 - very low to 5 - very high)
- `goout` : going out with friends (numeric: from 1 - very low to 5 - very high)
- `Dalc` : workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
- `Walc` : weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
- `health` : current health status (numeric: from 1 - very bad to 5 - very good)
- `absences` : number of school absences (numeric: from 0 to 93)
- `passed` : did the student pass the final exam (binary: yes or no)

-----

#### Requirements

This project requires **Python 2.7.15** and the following Python libraries installed:

- [Python 2.7.15](https://www.python.org/downloads/release/python-2715/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [scikit-learn 0.19.1](http://scikit-learn.org/stable/whats_new.html#version-0-19-1)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

-----

#### Execution

In a terminal or command window, navigate to the top-level project directory `Student-InterventionSystem/` and run one of the following commands:

```bash
ipython notebook report.ipynb
```  
or
```bash
jupyter notebook report.ipynb
```
or if you have 'Jupyter Lab' installed
```bash
jupyter lab
```

This will open the Jupyter/iPython Notebook software and project file in your browser.

-----

#### Furthur Additions 
In the future, we will try to build a recommendation system which will be able to suggest some of the intervention strategies that can be used to engage the students and help them to advance in their performance.

-----

#### NOTE:
* Clone or download the repository


* Tag me incase of using the data


* Tag me to use the above notebook's code for improvising
If you find my work good, useful and interesting, Be kind to star my work

### THANKYOU :)

