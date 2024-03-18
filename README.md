# TANZANIA WATER WELLS PROJECT
![bh-(1)](https://github.com/BKitainge/P-3-project/assets/123490766/56f3e007-8a08-4c2b-8d72-22a1f03a0ae5)
# Project Summary: Building a Classifier to Predict Water Well Conditions
Our client is an NGO focused on locating water wells that need repair in order to provide access to clean drinking water in rural areas. The client has provided us with a dataset containing information on various water wells, including their location, construction date, and various physical measurements such as depth and water volume. The goal of this project is to build a classifier that can predict the condition of a water well based on this information, in order to help the client prioritize which wells to repair first.

We will begin by exploring the dataset and conducting any necessary data cleaning and preprocessing. We will then perform feature engineering to extract relevant information from the dataset and transform it into a format suitable for modeling. Next, we will train and evaluate several classification models on the dataset, such as logistic regression, decision trees, and random forests, in order to determine which model performs best at predicting water well conditions.

Once we have selected the best performing model, we will fine-tune its hyperparameters using techniques such as grid search and cross-validation. Finally, we will use the trained model to make predictions on a holdout dataset and evaluate its performance using metrics such as accuracy, precision, and recall. We will also perform a cost-benefit analysis to determine the potential impact of using the model to prioritize water well repairs.

Overall, this project aims to provide our client with a tool that can help them more effectively allocate their resources towards repairing water wells in rural areas, ultimately improving access to clean drinking water for those who need it most.
## Column names
1. date_recorded - The date the row was entered

2. funder - Who funded the well

3. gps_height - Altitude of the well

4. installer - Organization that installed the well

5. longitude - GPS coordinate

6. latitude - GPS coordinate

7. wpt_name - Name of the waterpoint if there is one

8. num_private - Number of private waterpoints

9. basin - Geographic water basin

10. subvillage - Geographic location

11. region - Geographic location

12. region_code - Geographic location

13. district_code - Geographic loc

14. lga - Geographic location

15. ward - Geographic location

16. population - Population around the well

17. public_meeting - True/False

18. recorded_by - Group entering this row of data

19. scheme_management - Who operates the waterpoint

20. scheme_name - Who operates the waterpoint

21. permit - If the waterpoint is permitted

22. construction_year - Year the waterpoint was constructed

23. extraction_type - The kind of extraction the waterpoint uses

24. extraction_type_group - The kind of extraction the waterpoint uses

25 . status_group - Condition of the well
# Findings
The Random Forest algorithm, having the highest precision score of all performed better than the other models and shall be used as the final model The precision score of the model was 66% which means that it was able to precisely determine the status of the waterpoint 66% of the time
