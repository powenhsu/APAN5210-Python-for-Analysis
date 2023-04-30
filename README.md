@@ -1,6 +1,7 @@
# 5210Project
Group Project
Python For Data Analysis - Spring 2023

Due Date: May 1, 2023

Motivation
Expand All	@@ -15,6 +16,7 @@ You are given two datasets:
- left_dataset.csv
- right_dataset.csv
These datasets contain business names and their addresses.

The goal of this project is to find the businesses that are common to both datasets, that is, the
businesses that have a name and address that match between the left and right datasets.
Since the business names and addresses don't align perfectly between these datasets, you will
need to develop an algorithm that can find approximate matches. When your algorithm runs, it
should produce a list of triplets consisting of the entity_id from the left dataset, the business_id
from the right dataset, and a confidence score. The confidence score should have values
between 0 and 1.0 and convey a sense of confidence of the match. An identical match should have a score of 1.0.
Your submission should consist of matches that have a high degree of confidence, eg greater than 0.8.
# Summary
In this project, I applied Fuzzy Wuzzy matching technique and found 7164 highly matched ids (score higher than 0.8) in the left table of 98509 data and the right table of 94585 data.
Documents include:
left_dataset.csv
Right_dataset.csv
Function.py
5210_project_Python_Warrior.ipynb
