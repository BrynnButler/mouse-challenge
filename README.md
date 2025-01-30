# mouse-challenge
module 5

# Background
You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

# Instructions
This assignment is broken down into the following tasks:

Prepare the data.

Generate summary statistics.

Create bar charts and pie charts.

Calculate quartiles, find outliers, and create a box plot.

Create a line plot and a scatter plot.

Calculate correlation and regression.

Submit your final analysis.

# References
used Xpert Learning Assistance for guidance: 

my question: for homework module 5 challenge how do I get the table in the format it shows as the answer output (only showing 0-4)? I have # Create a clean DataFrame by dropping the duplicate mouse by its ID. clean_data = merged_data[merged_data["Mouse ID"] != "g989"] clean_data

what it gave me as an example:
display(clean_data.head(5))


my question: how do I avoid overlapping in xlabel for matplotlib?

what it gave me as an example:
plt.xticks(rotation=45, ha='right')

