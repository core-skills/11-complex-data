# CORE Skills Data Science Springboard - Day 11 - Special Data Types: Networks and Time series

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/core-skills/11-complex-data.git/master?urlpath=/lab/tree/notebooks/)

Today's session will introduce techniques to handle time series data. We will have a look at optimisation and genetic algorithms (GA), linear autoregressive models (AR), local constant models, and nonlinear global models. We will also discuss the complex network approach to time series data and how to use network properties to get insights about your data.  

You should aim to understand:

- The main features and limitation of computational optimisation and its importance for data science.
- How to implement a simple genetic algorithm.
- The distinction between prediction and simulation for time series analysis and the  several existing approaches.
- How to use the package **networkx** to calculate several network quantification measures and how to interpret the measures.
- The challenges and possible solutions for an industry scale network optimisation strategy.


## Pre-session Reading & Resources

We will use python notebooks exercises on different datasets to have a practical go on the discussed methods in practise. Have a go and check if everything is running on your machine before the class.  

For the complex network analysis, we will use **networkx**. You can find the documentation of  this package [here](https://networkx.github.io).

Stack Overflow is a useful website to find solutions for when you get stuck with python and libraries:
https://stackoverflow.com/questions/tagged/networkx
https://stackoverflow.com/questions/tagged/gdal.

**LinkedIn Data**:

For part of the exercises of today we will be anaylsing social network data. I will be using my own (public) LinkedIn network as an example, you may prefer to follow along with your own data. However, to do this you need to retrieve your data from LinkedIn. They will let you do this (``your data belongs to you''), but they don't make it easy and claim that the process takes 24 hours. If you want to do this (it is not compulsory) follow the following steps:
- Log into LinkedIn and go to Me -> Settings and Privacy -> How LinkedIn uses your data->Getting a copy of your data
- Enter your details (you'll need to reenter your password) and wait.
- LinkedIn will send you an email with details of how to obtain your data when the download is ready.

**Pre-reading**:

These are suggested pre-reading before the final case study of the day (session 4).

The Conversation:
**How tracking people moving together through time creates powerful data:**
[https://theconversation.com/how-tracking-people-moving-together-through-time-creates-powerful-data-103841](https://theconversation.com/how-tracking-people-moving-together-through-time-creates-powerful-data-103841)

**What it means when scientists say their results are ‘significant’:**
[https://theconversation.com/what-it-means-when-scientists-say-their-results-are-significant-103329](https://theconversation.com/what-it-means-when-scientists-say-their-results-are-significant-103329)

**References**:

Genetic Algorithms with Python - Clinton Sheppard.
Source code from the book: https://github.com/handcraftsman/GeneticAlgorithmsWithPython

M. Small. Applied Nonlinear Time Series Analysis: Applications in Physics, Physiology and Finance. Nonlinear Science Series A, vol. 52. World Scientific, 2005.

M. Small. Dynamics of Biological Systems., Mathematics and Computational Biology Series, Chapman & Hall/CRC, 2011.

Network Science by A.-L. Barabási: http://networksciencebook.com

Networks: An Introduction by Mark E. J. Newman
https://www.amazon.com/Networks-Introduction-Mark-Newman/dp/0199206651
