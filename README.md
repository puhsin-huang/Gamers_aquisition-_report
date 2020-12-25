# Gamers_aquisition_report

### Business Background & Goal:
A prospective mobile gaming client is looking to acquire new casual gamers for their jigsaw puzzle games.
TrueData’s goal is to build the best model possible to predict the users who are likely to have jigsaw puzzles installed.

Target variable is “desired_outcome” , which is defined as:
- 1 = Users who currently have jigsaw puzzle casual games installed
- 0 = Does not have jigsaw puzzle casual games installed

### Detailed implementation:

Please see the Report (TrueData_Deliverables_v2.pdf) for detailed information.

All detailed files can be accessed through: 
https://drive.google.com/drive/u/1/folders/1V2uJAWFR_KyfdEq4p1Ab8X5hh3v-rrC1

- Report: TrueData_Deliverables_v2.pdf (Models performance with different parameters combination is listed on slide_14)
- EDA code: TrueData_EDA_v2.ipynb
- Feature selection/Model building & Evaluation code: TrueData_Deliverable.ipynb
- Datasets: 
'demo_data.csv': Data with demographic features (~1M records)
'TrueData_rand_select.csv': randomly select 300 files from 3000 files to perform feature selection.
'data_recall40.csv': Data with the top 40 features (~1M records)
'df_Undersampling.csv': Model result using the undersampling technique.
'df_without_preprocessing.csv': Model result using data without preprocessing.
'feat_des.csv': top features identified in the feature selection step (noted that some features don't have an explanation provided. )
