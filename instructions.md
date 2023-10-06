# Instructions

You are part of a data analytics consulting firm called **NotGPT** (tagline *Human-focused data analytics*). 

Recently, a real estate company that has acquired various rental properties in Taipei City, Taiwan has contracted out your firm to extract an analysis of the housing market. 

To achieve this, your team has been tasked with analyzing and predicting an in-house dataset that your client has collected to figure out how much they should charge for their properties. Your coworker has completed some basic steps to this pipeline but now relies on your Python knowledge and documentation-reading skills to complete the rest.

This repository represents an incomplete data science project that aims to satisfy the project goal above. The sections below contain instructions as to what exactly you must complete.

This project version is the "normal difficulty." To tackle the "challenging" version instead, access the following [link](https://github.com/F-said/rental-pricing-explore-challenge).

Utilize documentation, your peers, readings, and classroom notes to complete this project. 

## Part 1: Exploratory Data Analysis

Firstly, you will fill in the missing code in `code/data_prep/explore.ipynb`. 

In almost all data science projects with prepared & structured data, we begin our process of data discovery by firstly "exploring" our dataset. This is a process called "[exploratory data analysis](https://en.wikipedia.org/wiki/Exploratory_data_analysis)" (EDA). 

In this process, you will generate various visualizations and metrics to get to know our dataset better.

You will notice that there are various missing pieces of code along with respective documentation.

Use the linked documentation and your Python knowledge to fill in these missing lines.

## Part 2: Data Preperation

After completing part 1, you will move on to `code/data_prep/clean.ipynb`. 

You should notice after our EDA step that there were some peculiarities with our dataset. Namely:

* A column was improperly interpreted as an "object" (aka string)
* The measures of our column reveal oddities such as negative convenience stores

These are most likely mistakes. We will discuss later how we can differentiate mistakes from actual data. For now, we will begin the process of removing these odd data points to move on to our modeling step.

Just like before, explore this file and fill in missing lines of code using the linked documentation.

## Part 3: Data Prediction

After cleaning our data, you can now move on to *modeling* & predicting our data.

By utilizing the documentation and examples, you will create a linear regressor that predicts the unit price of a rental property in this dataset.

## Part 4: Post Write-Up

Lastly, all good data science projects are flush with documentation where needed.

After completing the 3 parts above, you will move on to filling out the documentation in the `README.md` file. 

## Submission

The due date for this project is `10/16`.

To submit this project, you will push a completed version of this repository to your GitHub and post a link to your repo in Canvas.

**Note**: You must upload this to GitHub and submit a GitHub link to receive a grade for this project.
