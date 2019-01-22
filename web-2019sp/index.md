---
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

# CS 1380 + ORIE 1380 + STSCI 1380 <br/> Data Science For All <br/> Spring 2019

**Catalog Description:**
This course provides an introduction to data science. Given data from
economics, medicine, biology, or physics, collected from internet
denizens, survey respondents, or wireless sensors, how can one
understand the phenomenon generating the data, make predictions, and
improve decisions? We focus on building skills in inferential thinking
and computational thinking, guided by the practical questions we seek
to answer. The course teaches critical concepts and skills in computer
programming and statistical inference, in conjunction with hands-on
analysis of real-world datasets, including economic data, document
collections, geographical data, and social networks. We will also
consider social issues in data analysis such as privacy and design.

**Lecture:** TR 10:10-11:25 am in Kimball B11, starting January 22, 2019.

**Instructors:** [James Booth](http://faculty.bscb.cornell.edu/~booth/)
and [Andrew Gordon Wilson](https://people.orie.cornell.edu/andrew/)

{% comment %}

**Recitation:** Please attend the [recitation section](sections.html) in
which you are enrolled according to Student Center (*not* Scheduler or
CoursePad). Your partner for the three course projects must be from your registered
recitation section, so coordinate your registration accordingly.
Recitations meet starting January 23, 2018.

{% endcomment %}

## Topics and Course Objectives

A [schedule](schedule.html) of lectures and assignments is available.

This course is positioned at the intersection of computing and statistics,
with an emphasis on empirical analysis of real-world 
data sets through computation, rather than mathematical theory.
There are no prerequisites other than high-school algebra. 
As the Cornell motto says, we welcome "Any person...any study."

The course is organized into three units:

- *Exploration:* discovering and visualizing patterns in data.  Basic 
  Python programming, arrays, tables and table manipulation, 
  bar charts, scatter plots, line graphs, and histograms.
  
- *Inference:* drawing conclusions from data, and quantifying the
  reliability of those conclusions.  Experiments, randomized controlled trials, 
  association, causation, laws of probability, probability and empirical
  distributions, sampling, estimation of parameters, 
  variability, mean, median, standard
  deviation, the normal distribution, the Central Limit Theorem,
  hypothesis testing, *p*-values, confidence intervals, the bootstrap.

- *Prediction:* making guesses about unknown quantities
  based on data.  Correlation, linear regression, least squares,
  minimization, residuals, non-linear regression, multiple
  regression, dummy coding, nearest-neighbor classification,
  training vs. test data, accuracy.

**Outcomes:**

- Students will learn to communicate data visually and to
  interpret visualizations for themselves; and will practice 
  interpreting their discoveries in non-technical
  terms to people who are not data scientists.
  
- Students will analyze more than two dozen real-world data sets,
  from entertainment, sports, demographics, medicine, banking,
  transportation, voting, real estate, and sustainability.  
  
- Students will become familiar with Jupyter notebooks, which are 
  a standard tool for analyzing and presenting data; will learn simple
  procedural programming in Python; and will learn
  to use the `datascience` Python package for table manipulation and
  plotting.  The package is based on and simplifies the usage of Pandas
  and Matplotlib, which are standard packages for data science, while
  providing the possibility for a smooth transition to those packages in
  students' future work.
  
- Students will learn to conduct hypothesis tests by 
  correctly formulating null and alternative hypotheses,
  choosing test statistics, and empirically computing *p*-values
  through simulation.
  
- Students will learn to estimate population parameters, such
  as the mean and median; and to use the bootstrap to compute
  confidence intervals.
  
- Students will learn some basic properties of the normal
  distribution, including how to describe it with mean
  and standard deviation, standard units, a simple statement of the Central
  Limit Theorem, and how to choose sample sizes based
  on the square root law.  
  
- Students will learn to use linear regression to predict quantitative
  values, and to calculate and interpret the correlation coefficient,
  slope, and intercept of the regression line;
  and will learn to compute linear and non-linear regression models
  through numerical minimization of least-squares error.

- Students will learn to apply nearest-neighbor classifiers to predict
  categorical and quantitative values, and to implement such classifiers
  from scratch; and will learn some basic aspects of machine learning, including
  splitting data into training and test sets, and measuring the
  accuracy of a classifier.
  
## Answers to Some Important Questions

{% comment %}

If you have a question that isn't answered here, please
[register for the course's Piazza][piazza] and ask your question there.

[piazza]: https://piazza.com/cornell/spring2019/csoriestsci1380

{% endcomment %}

**Q:** Is it ok if I'm undeclared?  Or if I'm majoring in something other
  CS, ORIE, or Stats?  
**A:** Yes!  All majors are welcome, *especially* those from outside
  CS, ORIE, and Stats!

**Q:** Do I need to know a lot of math for 1380?  
**A:** Basic high school mathematics (e.g., Algebra I and II) is all you need.
  We won't use any calculus in 1380.

**Q:** Do I need to know how to program for 1380?  
**A:** Nope!  We'll teach you everything you need to know.

**Q:** Can I take 1380 if I've already taken a class on introductory programming
  (e.g., CS 1110) or stats (e.g., AEM 2100, ENGRD 2700, HADM 2010, ILRST 2100,
  MATH 1710, PAM 2100, STSCI 2100)?  
**A:** Yes, but if you've taken *both* programming and stats before,
  you're likely to find 1380 to move too slowly for you.
  You could instead consider INFO 2950, INFO 3300, CS 4780, ORIE 4740, or STSCI 4060.

{% comment %}

**Q:** I want to enroll but I have a conflict with the lecture, or I have
  conflicts with all the discussion sections.  
**A:** No, we won't be approving any concurrent enrollments, and you must
  be able to attend a discussion section.

**Q:** Can I enroll for one discussion section but attend another?  
**A:** No, you must attend the discussion section for which you are
  enrolled. To change your section you will need to officially enroll in a new
  section on Student Center.  

**Q:** I just signed up for the course on Student Center, but don't have access to 
  Vocareum yet. How can I get access faster?  
**A:** Sign up [here](https://goo.gl/forms/Gj4o4y5gUj9Pihge2), then monitor your 
  email for a message from Vocareum.  It might take up to 12 hours for your account
  to become active.

{% endcomment %}

## Acknowledgment

This course is based on [Data 8](http://data8.org), a course taught by
Ani Adhikari and John DeNero at the University of California, Berkeley. 
They and their teaching assistants have developed many of the materials
we are using in our own course.  We are using those materials with their
permission, which we gratefully acknowledge.
