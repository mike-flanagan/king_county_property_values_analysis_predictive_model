![image](https://user-images.githubusercontent.com/61798935/110903839-101ed380-82d6-11eb-8761-bee40d2f4369.png)  
  
<div align="center";>Photo by Luca Micheli on Unsplash</div>  
  
## Overview  
This project develops a predictive model for property values in King County in Seattle, WA. I used statistical analysis to develop a predictive model that is tested on a holdout dataset.

## Motivation  
To see if property sales in King County may be predicted using data from former property sales.

## Data  
The testing dataset used includes multiple features for several thousand property sales in King County. The holdout dataset contains several thousand different properties also in King County, and had all features of the testing dataset except for property sale price. With the final model, I was able to export a csv file of predicted sale prices that correspond with the properties in the holdout dataset.

## Methods  
My methodology implements the CRISP-DM model for exploratory data analysis, cleaning, modeling, and evaluation. I use descriptive and inferrential statistics to evaluate a test dataset, including hypothesis testing with t-tests and analysis of variance. From my inferrences, I developed predictive models with use of polynomial features, categorical dummy variables, as well as several engineered features. Finally, I deployed and evaluated linear regression models using a filter method F-test to find K best, and wrapper method recursive feature elimination cross-validation. Models were evaluated primarily on the RMSE of training and testing data in a train-test-split.  
  
Tools used include Python, NumPy, Pandas, SciPy, StatsModels, and SciKit Learn. Visualizations were created with MatPlotLib and Seaborn.  

## Index
- **data/** — houses datasets used throughout project.  
  - **housing_preds_Mike_Flanagan.csv** — final predictions on the holdout dataset  
  - **kc_house_data_test_features.csv** — holdout dataset used to implement final model  
  - **kc_house_data_train.csv** — dataset used to develop predictive model  
- **EDA/** — houses initial EDA notebook file  
  - King_County_CRISP-DM-EDA.ipynb** — notebook file that includes thorough initial data exploration, insights, and takeaways  
- **images**  
  - _King_County_Analysis_Mike_Flanagan.pdf — pdf of presentation slides for initial EDA takeaways  
  - image exports of visualizations  
- **FINAL_KC_Predictive_Model_Mike_Flanagan.ipynb** — primary project notebook  
- **KC_Holdout_Data_Predictions.ipynb** — holdout data notebook where final predictive model was executed  
- **features.pickle** — save file of features used in final model  
- **model.pickle** — save file of final model  
- **README.md**  




Author — Mike Flanagan  
https://github.com/mike-flanagan/


