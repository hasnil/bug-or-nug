This repository holds files used in the completion of a project entitled "BUG or NUG: An Extension of Previous Work Regarding the Classification of Software Issue Reports using Supervised Machine Learning"

# Overview

Databricks Notebook Link: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2870846592495035/3972701098927942/75685322812263/latest.html

Issue reports are often submitted by testers, software developers and customers to issue trackers, like JIRA's defect tracking tool, describing problems that need to or should be addressed in software. Typically, these issues are classified properly according to their nature. However, requests for improvements or new features are often misclassified as bugs. This is costly to developers as they can end up expending time and effort on issues that are not as vitally important as serious bugs. Automatic classification using machine learning algorithms could be employed to greatly reduce the occurrence of misclassifications and thereby improve developer productivity, with broader potential benefits in a variety of fields. 

The purpose of this project was to analyze how different machine learning algorithms, namely Naïve Bayes, Linear SVC and Random Forest, could perform in assisting automation of the binary BUG or NUG (not a bug) classification task, based on the text of issue summaries. The PySpark API was used.

The new data for this report was manually collected from JIRA trackers for MongoDB, Apache Spark and Wildfly. Issue reports each had four pieces of information recorded: SUMMARY, ID, TYPE and CLASSIFIED. This was combined with pre-existing data from the first source listed below.

## Sources

Nitish Pandey, Debarshi Kumar Sanyal, Abir Hudait, and Amitava Sen. Automated classification of software issue reports using machine learning techniques: an empirical study. Innovations in Systems and Software Engineering, 13(4): 279-297, 2017.

Kim Herzig, Sascha Just, and Andreas Zeller. It’s not a Bug, it’s a Feature: How Misclassification Impacts Bug Prediction. Proceedings of the 2013 International Conference on Software Engineering(ICSE’13), 392-401, 2013.

Dksanyal. BugBang. https://github.com/dksanyal/BugBang, 2018.

## Team Members

Lotfi Hasni

Aaron Joseph

Alan Joseph

