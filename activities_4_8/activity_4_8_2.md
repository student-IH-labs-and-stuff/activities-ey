# 4.08 Activity 2

- continuing with the data source `files_for_activities/finalMergedFile.csv` in PowerBI
- get more data - as you saw in the lesson, bring in the df_final_experiment_clients.csv file 
- explore the model view
- get more data - adding df_final_web_data_pt_1.csv - add a transformation step which retains only the Confirm process step 
- close and apply
- review the model view - how do the relationships differ between the tables ? has a relationship between the two recently added sources been detected?
- if no relationship exists go into Manage Relationships > New relationship > add relationship 1 to many from client in df_final_experiment_clients.csv and client in df_final_web_data_pt_1.csv 
- remove the relationship detected from the previous step between df_final_experiment_clients.csv to the finalMergedFile.csv but retain the relationship between the two raw data sources 
- create a summary table showing the total number of clients cross referenced to the total number of clients who reached the confirm step in the experiment (test or control) using count distinct in each case
- rename the measures for this visual only to make it clearer 

