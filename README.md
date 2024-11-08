<a class="anchor" id="0"></a>

# **Extensive Analysis + Visualization with Python**

Hello,


**Heart disease** or **Cardiovascular disease (CVD)** is a class of diseases that involve the heart or blood vessels. Cardiovascular diseases are the 
leading cause of death globally. This is true in all areas of the world except Africa. Together CVD resulted in 17.9 million deaths (32.1%) in 2015. 
Deaths, at a given age, from CVD are more common and have been increasing in much of the developing world, while rates have declined in most of the 
developed world since the 1970s.

So, in this kernel, I have conducted **Exploratory Data Analysis** or **EDA** of the heart disease dataset. **Exploratory Data Analysis** or **EDA** is 
a critical first step in analyzing a new dataset. The primary objective of EDA is to analyze the data for distribution, outliers and anomalies in the 
dataset. It enable us to direct specific testing of the hypothesis. It includes analysing the data to find the distribution of data, its main 
characteristics, identifying patterns and visualizations.  It also provides tools for hypothesis generation by visualizing and understanding the data 
through graphical representation.  

I hope you see something new and enjoy this kernel.



<a class="anchor" id="0.1"></a>

## Table of Contents


The table of contents for this project are as follows: -

1.	[Introduction to EDA](#1)
1.	[Objectives of EDA](#2)
1.	[Types of EDA](#3)
1.  [Import libraries](#4)
1.	[Import dataset](#5)
1.	[Exploratory data analysis](#6)
      - [Check shape of the dataset](#6.1)
	  - [Preview the dataset](#6.2)
	  - [Summary of dataset](#6.3)
      - [Dataset description](#6.4)
      - [Check data types of columns](#6.5)
      - [Important points about dataset](#6.6)
      - [Statistical properties of dataset](#6.7)
      - [View column names](#6.8)
1.	[Univariate analysis](#7)
      - [Analysis of `target` feature variable](#7.1)
      - [Findings of univariate analysis](#7.2)
1.	[Bivariate analysis](#8)
      - [Estimate correlation coefficients](#8.1)
      - [Analysis of `target` and `cp` variable](#8.2)
      - [Analysis of `target` and `thalach` variable](#8.3)
      - [Findings of bivariate analysis](#8.4)
1.	[Multivariate analysis](#9)
      - [Heat Map](#9.1)
      - [Pair Plot](#9.2)
1.	[Dealing with missing values](#10)
      - [Pandas isnull() and notnull() functions](#10.1)
      - [Useful commands to detect missing values](#10.2)
1.	[Check with ASSERT statement](#11)
1.	[Outlier detection](#12)
1.	[Conclusion](#13) 
1.	[References](#14)
