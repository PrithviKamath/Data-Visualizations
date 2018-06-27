# Tableau Visualization on titanic Survivors Dataset
</br  >
<b>Dataset Overview</b>: RMS Titanic disaster was one of the worst shipwrecks in the history of mankind. With not enough lifeboats for the passangers and crew, the ship sank killing 1502 out of its 2224 passengers and crew. I have used this dataset from kaggle.com to visualise the survivor counts based on Sex, Age, Where the passenger embarked the ship from and which class the passenger belonged to.</br  >
<img src='https://github.com/PrithviKamath/Data-Visualizations/blob/master/Titanic%20Survisors%20with%20Tableau/Images/Titanic.jpg'></img> </br  >
</br  >
Since there seemed to be a few missing values in the dataset, I have used Python to perform data cleaning and data wrangling, as visualizing blank values in a sunburst chart is incorrect.</br  >
</br  >
My steps were as follows:</br  >
•	Check for the count of null values</br  >
•	As we understand that there are just 2 'null' entries in the Embarked column, we fill it with the highest occuring value ie the mode of Embarked (value = 'S' which represents Southampton)</br  >
•	Next we move to the Age column where there are 177 missing values. We replace the missing values with 100. We shall be filtering out these values from the sunburst chart so that the overall count is unaffected.</br  >
•	Also we understand that Age valries from 4 months to 80 years and hence visualizing every year would not be the right approach. Hence we bucket age into Age_Bins for 10 years each and obtain 8 bins.</br  >
</br  >
Now we move on to the Data Visualization part with Tableau.</br  >
</br  >
Sunburst charts require data to be presented in a pivot table with Outline Form shown and all Item Labels repeated.</br  >
<img src='https://github.com/PrithviKamath/Data-Visualizations/blob/master/Titanic%20Survisors%20with%20Tableau/Images/TitanicSunburst.png'></img>
</br  >
Reference:</br  >
•	Titanic Survival Dataset: https://www.kaggle.com/c/titanic-survival/data</br  >
•	https://www.superdatascience.com/yt-tableau-custom-charts-series/</br  >
•	Titanic Image: https://www.britannica.com/topic/Titanic</br  >
