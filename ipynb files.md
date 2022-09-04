ReadData.ipynb: Preprocess the initial data, mainly adding two indexes, surival time and event. Generate "survival_data.csv"

ReadResults.ipynb: Basaed on the added two indexes, do KM analyis

Single_SurvivalModel_Step1.ipynb: Preprocess and generate "survival_data_filtered_1.csv" and "survival_data_filtered_2.csv"

Single_SurvivalModel_Step2.ipynb: Further filter labels and generate "survival_data_filtered_3.csv"

Single_SurvivalModel_Step3.ipynb: Based on survival_data_filtered_3.csv, do DeepSurv analysis

Single_SurvivalModel_AllinOne.ipynb: Combine "Single_SurvivalModel_Step1.ipynb", "Single_SurvivalModel_Step2.ipynb", and "Single_SurvivalModel_Step3.ipynb"

CrossValidation_SurvivalModel.ipynb: the cross validation version of "Single_SurvivalModel_AllinOne.ipynb", and generate "feature_selection.csv", "performance_CI.csv", and "performance_IBS.csv"

CrossValidation_SurvivalModel_Single.ipynb: single seed version of "CrossValidation_SurvivalModel.ipynb"

ReadData_basicINFO.ipynb: Basic information of NACC samples

UsedGroupInfo.ipynb: Group information about shift and non-shift

UsedGroupInfo_FS.ipynb: ANalysis of features in groups of "UsedGroupInfo.ipynb"

FS_Show.ipynb: Visulization of top selected features