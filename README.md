# IECSE-Enigma-2021-Machine-Learning

Enigma is the Machine Learning competition of IECSE Manipal's flagship event - Prometheus!

Prometheus X was based on battling the underworld tycoons ruling over different continents. In Enigma, our agenda was to expose the Mafia ruling over Asia by building the best model to move up the leaderboard in the competition held on Kaggle.

Engima took place over a span of two days:

## Day 1: Classification

Link to the competition: https://www.kaggle.com/c/enigma-2021-day-1

### Problem Statement: 
The elite 10 Luxury Conglomerates reported USD 144 billion in revenue from luxury good in 2019 FY, and the luxury goods market has been on a perpetual upward trend. Few can afford these luxury products, and even fewer can manage to produce these high-end products. Owning these products have always been prestigious and are the epitome of desirability.

The Mafia has been selling exact replicas of various high-end products such premium sneakers, exquisite jackets, swiss watches, stylish handbags, haute-couture clothes etc. The Mafia has continuously earned hefty profits from this operation and virtually causing loss worth billions to these companies. They further use this money to fund illegal operations all over Asia. You are part of the Asian Federal Trade Control's (AFTC) Bureau of Consumer Protection.

You have been assigned to scrutinize and detail to gather intel about the Mafia's operations. The counterfeit products are incredibly identical to the original ones, and the Mafia would do anything in its power to keep selling them.

The given [data](/Classification/Classification_Data.csv) contains certain attributes you need to determine which of the products are counterfeit to track down the chain of operation.

### [My Model:](/Classification/Classification_Notebook.ipynb)

I constructed a Pipeline to predict the class of the dependent variable using Random Forest Classifier after transforming the numerical columns using Simple Imputer and Robust Scaler and the categorical columns using Simple Imputer and One Hot Encoder and calculated the Accuracy Score using the testing data specified.

<br></br>

## Day 2: Regression

Link to the competition: https://www.kaggle.com/c/enigma-2021-day-2

### Problem Statement:
Your previous endeavours bore fruit. With your help, the investigators have traced the products identified as counterfeit, and they have narrowed it down to what they believe are the Mafia owned factories. You have been given data collected by these investigators. You must come up with a way to show that the profits earned far exceed the ideal profit earned by a company creating original products, considering the use of high-quality raw material. Use the [data](/Regression/Regression_Data.csv) from the other factories to predict the ideal profit to prove the fraudulence of these companies.

You need to predict the ideal profit earned by each factory showing the discrepancy, giving you the evidence to shut down the Mafia operations.

### [My Model:](/Regression/Regression_Notebook.ipynb)

I constructed a Pipeline to predict the values of the dependent variable using Random Forest Regressor after transforming the numerical columns using Simple Imputer and Robust Scaler and the categorical columns using Simple Imputer and One Hot Encoder and calculated the Root Mean Square Error using the testing data specified.

<br></br>

***All the credits for hosting the competition, forming the problem statement, and constructing the dataset go to IECSE.***

