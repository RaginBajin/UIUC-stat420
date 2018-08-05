This is the final project. This is my public archive of the work that went into the final project. 
It has been cleaned up to avoid the unnecessary grading information. 



***

# STAT 420: Data Analysis Project


## Data Selection
You may use any dataset of your choice, so long as it contains at minimum 200 observations, has a numeric response variable, at least one categorical predictor, and at least two numeric predictors. This dataset might be relevant to research outside of this course, another field, or some other interest of yours. It will be helpful if you have a few questions in mind and that the data that you select is relevant to those questions.

If you have any questions about whether your data meets the specifications given above, don’t hesitate to ask. If you plan to use data from another endeavor of yours, such as a research project, be sure to gain permission from the controlling authority first.

Some potential data sources:

Data.gov
Centers for Disease Control and Prevention
StatSci.org
NIST’s Statistical Reference Datasets (StRD)
U.S. Census Bureau
U.S. Bureau of Labor Statistics
Inter-university Consortium for Political and Social Research
Data Counts!
MathForum.org Data Library
DASL Data and Story Library (data, software, and news from the statistics community)
Sports-Reference family of sites
If you find alternative sources for good datasets, please post about them in the forums!

## Analysis
The final product of this project will be a written report of your analysis. It should contain the following sections:

Introduction
Methods
Results
Discussion
Appendix
The introduction section should relay what you are attempting to accomplish. It should provide enough background to your work such that a reader would not need to load your data to understand your report. Like the simulation project, you can assume the reader is familiar with the course concepts, but not your data. Some things to consider:

What is this data? Where did it come from? What are the variables? Why is it interesting to you?
Why are you creating a model for this data? What is the goal of this model?
The methods section should contain the bulk of your “work.” This section will contain the bulk of the R code that is used to generate the results. Your R code is not expected to be perfect idiomatic R, but it is expected to be understood by a reader without too much effort. Use RMarkdown and code comments to your advantage to explain your code if needed.

This section should contain any information about data preparation that is performed to the original data before modelling. Then you will apply methods seen in class, which may include some of the following but are not limited to:

Multiple linear regression
Dummy variables
Interaction
Residual diagnostics
Outlier diagnostics
Transformations
Polynomial regression
Model selection
Your task is not to use as many methods as possible. Your task is to use appropriate methods to find a good model that can correctly answer a question about the dataset, and then to communicate your result effectively.

The results section should contain numerical or graphical summaries of your results. You should report a final model you have chosen. There is not necessarily one, singular correct model, but certainly some methods and models are better than others in certain situations. You may use any methods we studied this semester to complete this task, and provide evidence that your final choice of model is a good one.

The discussion section should contain discussion of your results and should frame your results in the context of the data. How is your final model useful?

The appendix section should contain code and analysis that is used, but that may clutter the report or is not directly related to the choice of model.

## Task Specifics
Data Analysis Project Proposal
A proposal of your intended project is due by Monday, July 17, 11:59 PM.

After review of the proposal, it will be evaluated in one of two ways:

Approved - Your group may proceed with your plans for the data and project.
Pending - We will provide suggestions, concerns, or needed information that must be addressed before the proposal will be approved.
A proposal of your intended project should include the following:

The names and NetIDs of the students who will be contributing to the group project
A tentative title for the project
Description of the dataset. You do not necessarily have to list all the variables, but at least mention those of greatest importance.
After reading the proposal, a reader should have a good understanding of your dataset without needing to reference the data itself or other documentation.
Background information on the dataset, including specific citation of its source
A brief statement of the business, science, research, or personal interest you have in the dataset that you hope to explore
Evidence that the data can be loaded into R. Load the data, and print the first few values of the response variable as evidence.
As a group, you will submit a .zip file as you would for homework that contains an .html and .Rmd file, as well as the data if it cannot be linked online. If your data is too large to submit and cannot be linked, please let us know and we will find an alternative.

Data Analysis Project Report
The final written report of your analysis as described above is due by Friday, August 4, 11:59 PM.

As a group, you will submit a .zip file as you would for homework that contains an .html and .Rmd file, as well as the data if it cannot be linked to online. Be sure to give your report a title and include the names of all group members.

FAQ
How long should the report be?

You’ll be creating an html file, so there’s no such thing as a page count, and we’re not concerned with that anyway. On one hand, you need to provide results and evidence to support your decisions, and you need to be thorough and diligent as you walk through the steps of finding your best model. On the other hand, a well-crafted data analysis will utilize brevity and conciseness. If you have a point to make, get to it. If you find yourself writing things simply for the sake of padding the word count, you’re writing the wrong things. This project is intentionally open-ended to see how you do without being given explicit steps, so have fun building your model.