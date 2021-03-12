![image](https://user-images.githubusercontent.com/61798935/110971972-7d0f8900-8329-11eb-92f4-1c9a6a4c4c62.png)  
  
<div align="center";>Photo by Luca Micheli on Unsplash</div>  
  
## Overview  
This project develops a predictive model for property values in King County in Seattle, WA. I used statistical analysis to develop the model that is tested on a holdout dataset.
  
## Motivation  
To see if property sales in King County may be predicted using data from former property sales.
  
## Data  
The testing dataset used includes multiple features for several thousand property sales in King County. The holdout dataset contains several thousand different properties also in King County, and had all features of the testing dataset except for property sale price. With the final model, I was able to export a csv file of predicted sale prices that correspond with the properties in the holdout dataset.
  
## Methods  
My methodology implements the CRISP-DM model for exploratory data analysis, cleaning, modeling, and evaluation. I use descriptive and inferrential statistics to evaluate a test dataset, including hypothesis testing with t-tests and analysis of variance. From my inferrences, I developed predictive models with use of polynomial features, categorical dummy variables, as well as several features engineered from those that were available in the dataset. Finally, I deployed and evaluated linear regression models using a filter method F-test to find K best, and wrapper method recursive feature elimination cross-validation. Models were evaluated primarily on the Root Mean Square Error of training and testing data in a train-test-split.  
  
Tools used include Python, NumPy, Pandas, SciPy, StatsModels, and SciKit Learn. Visualizations were created with MatPlotLib and Seaborn.  
  
## Conclusion  
After running and evaluating different models, I selected the model which returned the lowest RMSE. The model was saved using pickle, then imported in to the holdout notebook, where it generated predictions for property sale prices. These predictions were exported to the **data/** folder as a csv file and will be evaluated against the true sale price of all properties in the holdout dataset.  
  
## Further Actions  
Once the holdout data predictions are evaluated, I would again step through the CRISP-DM process to see if the model could be improved. There is no one correct approach to evaluating and using the data, but to go further, it would be useful to improve my domain expertise in real estate, develop a deeper familiarity with the market in King County, and utilize the insights of others who may have a different creative approach. In the final notebook, I have outlined other thoughts on how the model could be improved with more ideas on cleaning and feature engineering.  
  
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
  
  
  
<div align="center";>Author  
  <div align="center";>Mike Flanagan  
<div align="center";><a href="[GitHub](https://github.com/mike-flanagan/) | [LinkedIn](https://www.linkedin.com/in/mike-flanagan-data/)"</a>
  
  
