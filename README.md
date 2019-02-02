---
title: Machine Learning in Physics
---

This is to facilitate the “Machine Learning in Physics” course that I am
teaching at Sharif University of Technology for winter-19 semester. For more
information, see the course page at

<http://sharif.edu/~sraeisi/ML>

Requirements:
=============

-   Decent understanding of programming and python syntax and the following
    libraries

    -   Numpy

    -   Pandas

    -   Plotting and graphical presentation tools in python

-   Git and Github (if you not familiar, let me know.)

-   Basic understanding of quantum mechanics and statistics.

-   Basic understanding of machine learning

Marking Scheme
==============

This is a tentative plan and we may change it as we move on.

-   Course Project: 40%

-   Assignments: 30%

-   In-class exercises 10%

-   Final exam: 30%

These add up to 110% which include the bonus as well.

Course Projects
===============

This is a group project and counts towards 40% of the final grade.

The idea is that each group decides on a project at the beginning of the course
and apply everything that we cover to their project. Here are some of the
expectations for the course project:

-   Some initial proposal: Clear statement of the problem and some primary
    assessment of why using ML could help answer this problem.

-   Data collection/generation and preparation:

-   Application of the basic ML techniques

    -   A table of assessment (Will give an example later.)

    -   Investigation of variance and bias of the techniques investigated.

    -   Learning and validation curves

-   Oral presentation

-   Written term paper

Table of contents 
==================

The course material is posted here and you can use either [Google
Colab](http://colab.research.google.com/) or [Mybinder](http://mybinder.org/) to
work with these Jupyter notebooks.

| Topic                                 | Lectures                                                                                                                                                                                              | Notebook(s) |
|---------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| Basics of machine learning            | Lec_1: Introduction and notation Lec_2: Regression, logistic regression and classification, overview and practical tips Why? ML beyond simple examples Overview of some of the most common techniques |             |
| Data Preparation                      | Collection and generation Standardization Clean-up: nan and outliers Data reduction: PCA, variance threshold …                                                                                        |             |
| Concepts from Statistical learning    | Variance and bias Learning curves Model selection and validation curve Practical methods for dealing with overfitting Bayesian inference                                                              |             |
| A few tools before we get down to it… | Cost functions                                                                                                                                                                                        |             |
| Neural Networks                       | Feedforward:                                                                                                                                                                                          |             |
| Convolutional Neural Networks         | Basic Idea and details Example(s)                                                                                                                                                                     |             |
| Recurrent Neural Network              | Basic Idea and details Example(s)                                                                                                                                                                     |             |
| Reinforced Learning                   | Basic Idea and details Example(s)                                                                                                                                                                     |             |

-   Optimization algorithms

-   Model

-   Geometry and formulation

-   Universality

-   Non-linearity: Activation function

Back propagation

-   Details

-   Initialization

-   Optimizations

-   Batch and epoch

-   Couple of example

Practical implementations:

-   TensorFlow and Keras

Cheat sheets and guides
=======================

See the files in the CheatSheet folder.

| Item                                  | Description                                                                                                                                                        |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Jupyter                               | It provides an interactive environment for programming. We will be mostly using the python 3 kernel.                                                               |
| Git and Github                        | Git provides a strong infrastructure for version control. Github is web-based hosting service for version control and it also provides services for collaboration. |
| Python                                | It is the programming language that we will be mostly using for this course.                                                                                       |
| NumPy                                 | It’s a python library that provides strong and efficient tools for manipulation of high-dimensional arrays.                                                        |
| SciPy                                 | It’s a python library, built on NumPy for mathematical and scientific computing.                                                                                   |
| Pandas_basics Pandas 2 Importing data | It’s a python library, built on NumPy that provides efficient tools for handling and analysis of data.                                                             |
| Matplotlib Seaborn                    | These are two of the most common python library for visualization.                                                                                                 |
| Scikit-Learn                          | It’s a python library that provides a nice and fairly efficient implementation of most the machine learning techniques and ideas.                                  |
| Keras                                 | It is python library that provides a high-level and easy-to-use interface for Tensorflow and some other deep learning libraries.                                   |