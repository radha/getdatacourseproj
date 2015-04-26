# getdatacourseproj
1. Load feature labels from featueres.txt
2. Load test datafrom X_test.txt using colnames from step 1
3. load training data from X_train.txt
4. merge data from steps 2 and 3 using r bind to make a single dataset
5. extract only mean and standard deviation columns for each feature
6. load activity for each test observation from y_test.txt
7. load activity for each training observation from y_train.txt
8. merge data from steps 6, 7
9. read activities labels from activity_labels.txt
10. replace activity code with descriptive name 
11. load subject code for each test observation
12. load subject code for each training observation
13. merge data from step 11, 12
14. prefix subject code and activity label columns to the data set from step 5
15. make long version od dataset suitable for summary calculations
16. summarize by activity and subject, taking average for each variable, aactivity, subject combination
17. write wide form of summarized dataset to summary.txt
