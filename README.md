# UT-Data-Science-Assignment
This repository is created for the Data Science course at the University of Tehran.

Students should fork this repository and upload reqired assignment files due to the tasks introduced after each session.

The Final Score for each assignment is calculated as described here: You have 100 points at first. For missing each task's main activity you lose 10 points and having minor mistakes reduces 5 points of your starting points.This will be your score as "Completeness" of assignment. After calculating the completeness of assignment, you lose 2.5% of your score for each extra commit you had and 0.5% for each hour you delayed doing the assignment.

The Final Score will be the average of all the assignments scores.

Good luck.

-------------------------------------

Session 2 Assignment: To complete this assignment you have to upload 2 files to your Github repository (forked) and share the link to your repo to complete tasks 1 to 4. Also you have to share the link to your KNIME forum profile whenever task 5 is completed.

Task 1: Read the "adult.csv" file using "File Reader" node. The output data MUST contain only first 30,000 rows and all columns MUST be labeled.
  
Task 2: Read "cars-85.xlsx" file using "Excel Reader (XLS)" node. In the output data, the first 2 columns MUST be skipped.

Task 3: Read "Iris.sqlite" database file using appropriate nodes. The output data MUST caontain only the following columns:
"sepal_length", "sepal_width", "petal_length", "petal_width", "class_Arr_1_"

Task 4: Add "Node Monitor" view to the right panel. Take a screenshot while this view is added in KNIME Analytics Platform.

Task 5: Sign up for a KNIME Forum account and get "Autobiographer" and "First Like" badges.

-------------------------------------

Session 3 Assignment: To complete this assignment you have to upload 1 file (.knwf) to your repo.

Task 1: Remove row limit in "File Reader" node and column limit in "Excel Reader". (These limitations were done in the previous assignment)

Use Iris.sqlite to do the rest of tasks:

Task 2: Use "Color Manager" node to assign colors to Classes (setosa, versicolor, virginica) in Iris dataset.

Task 3: Use a "Scatter Plot" node and select "sepal_width" as x axis and "petal_width" as y axis and then select the one single point which is not close to other points in "setosa" class. Save changes as default configuration.

Task 4: Filter and exclude the row which was selected in the previous task.

Task 5: Use the "GroupBy" node to calculate the mean of "sepal_length", "sepal_width", "petal_length" and "petal_width" for each class in Iris dataset.
