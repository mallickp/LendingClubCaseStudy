# LendingClubCaseStudy

## Objective
Lending Club Case study is about an organization that is invovled in approving providing loans to individuals, based on the application that come from them. The ultimate aim is to mitigate credit rsik.  

To put it very simply, credit risk refers to the risk of loss that a lender faces due to a borrower’s failure to repay any type of loan or debt. In the personal lending space, the practice of credit risk assessment deals with ascertaining whether or not an individual should be awarded a certain amount of credit. Lending to a risky applicant who would not pay the money back would result in huge financial loss for the organization. This leads to the fact that a thorough risk analysis would be required before a loan is approved or disapproved. This decision making is primarily based on the analytics build on top of the data set. 

The main objective is to be able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. 
Consuming EDA as the primarily tool for performing these analysis and coming to a dedicated concludsion is the aim of this case study. 

## Table of Contents
* [General Info](#general-information)
* [Introduction](#introduction)
* [Technologies Used](#libraries-used)
* [Overview Of Analysis](#overview-of-analysis)
  * [Basic visualization of data ](#basic-visualization-data)
  * [Categorizing the data](#categorizing-data)
  * [Data Cleansing ](#data-cleansing)
  * [Derivied Variables](#derived-variables)
  * [Segmented Univariate Analysis](#segmented-univariate-analysis)
  * [Bivariate Analysis](#bivariate-analysis)
  * [Plotting for visualization](#plotting-for-visualization)
  * [Filtering data](#filtering-data)
  * [Correlation](#correlation)
* [Conclusions](#conclusions)
* [Contributors](#contributors)



## General Information

  Project is primarily aimed at helping a lending organization come up with a data analysis model which can be help them mitigate risk of financial loss by lending loans to risky applicants. 
  
- What is the background of your project?

  The usecase is primarily designed to evaluate our understanding of EDA and how to implement the various concepts that we learnt in solving a real world problem. 
  
- What is the business probem that your project is trying to solve?

  Helping a lending organization make rational decisions on approving loans, to mitigate financial loss. 
  
- What is the dataset that is being used?

  Complete loan data for all loans issued through the time period 2007 t0 2011.

## Basic Visualization of Data

First and foremost step to perform when we get access to a data set is to visualize and understand the content present in it. Focus on the metadata, columns data and so on. In the program, we try to utilise various visualization techniques to consume the data for basic understanding.

## Categorizing the Data

We have tried to categorize the data into three parts: 
1. Variable related to Applicants ( Demographics i.e age,employee details,occupation)
2. Loan characterstics ( Type of loan, Amount requested,Interest loan,purpose of loan)
3. Customer behavior varaibles (those which are generated after loan is sanctioned delinquent 2 years,revolving balance, next payment etc).

Now the customer behavior variables will not be available during loan application request, so they can not be used to predict the credit approval.

## Data Cleansing

The next step here would shocase how the data present in the data set can be made more accurate by implementing various cleansing techniques. 

## Univariate Analysis

Consuming the concepts of Univariate Analysis, we try to bring in some early inference on the data set shared. 

## Derived Variables

In addition to the existing columns, we try to infer additional columns based on the existing ones, that could be used for coming up with relevant data for analysis.

## Bivariate Analysis

Consuming the concepts of Bivariate Analysis, we try to bring in some early inference on the data set shared. 

## Plotting for Visualization

With the support of vairous graphical representations, we try to plot the data to make relevant inferences. 

## Correlation

Finally, we try to plot a correlation matrix, to get an indepth view inot the impact of each variate we have taken into consideration. 


## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis


## Libraries Used
- Numpy 
- Pandas 
- Matplotlib
- Seaborn
- plotly

## Contributors
- Prabir Kumar Mallick [@mallickp]
- Sreejith Rajashekaran [@sreejith-rajashekaran]
