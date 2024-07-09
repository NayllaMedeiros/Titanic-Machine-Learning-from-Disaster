# Titanic-Machine-Learning-from-Disaster
Repository created for Kaggle competition 

## Introduction
This project was created as a competition on Kaggle with the goal of using machine learning to create a model that predicts which passengers survived the sinking of the Titanic.

## The Challenge
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we were asked to build a predictive model that answers the question: “what types of people were most likely to survive?” using passenger data (i.e. name, age, gender, socioeconomic class, etc.).

## Requirements
For this project I used:
* **Python, Notebook 3.6**
* **Pandas**
* **Numpy**
* For the graphics I imported:
* **(`import seaborn as srn`)**
* * For forecast models:
* **from sklearn.model_selection ('import train_test_split')**
* **from sklearn.linear_model ('import LinearRegression')**
* **from sklearn.ensemble ('import RandomForestClassifier')**
* * For to clean:
  **from sklearn.preprocessing import MinMaxScaler**
  **from sklearn.preprocessing import OneHotEncoder**

  ## Clean
  For to clean the datas, I first imported the data, then visualized it, observed its types and then started cleaning.
1. I cleaned the data that was empty, putting the median in some and the mode in others
2. I viewed graphs to find out if there were outliers that needed to be eliminated
3. I did standardization/normalization on some data that was very dispersed
4. I used feature engineering to transform string data to float
5. Finally I removed the columns that were not necessary

  ## Models and Predictions
   After cleaning the data, I created a prediction model, in this case I used Random Forest
   To do this, I separated the variables, divided them into training and testing, trained the model with the training base that was available in csv, and with that I obtained a success rate of 0.81
   Then I used the test base also available in csv, cleaned it the way I had done in the training base, and then put my model to predict which people would survive on the titanic

  ## Conclusion
   At the end of the project, a subscription must be made on the competition website, and there a score will be assigned according to how correctly the model was able to predict who will survive.
   I reached a score of 0.78, and so my goal now is to try to improve my model's prediction.
   
