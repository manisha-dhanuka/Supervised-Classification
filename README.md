# Supervised-Classification Project 1

# Project Information:
Android is the most popular operating system in the world, with over 2.5 billion active users spanning over 190 countries. Created by Andy Rubin, it quickly became the favorite OS for most of the mobile manufacturers in the early 2010’s. Being favorite of so many users, the statistics of having highest malware rate i.e., 47.15% of all vulnerable devices is a concern for android mobile users. 
	In this project, we develop a model using machine learning techniques that can differentiate between the malware apps and the benign ones.
  
# Problem Statement: 
The dataset consists of nearly 30,000 apps from various sources: Google's play store, hiapk, app China, Android, mumayi, gfan slideme, and pandaapp along with the extracted permissions with the package. 

The main objective is to find on the basis of these features what apps are the problem creators for the Android users.

# Project Overview:
1.	Data Cleaning

      •	Handling Null values
      
      •	Duplicates Consideration

2.	Data Exploration- Univariate Analysis:

      •	Qualitative measures of Data i.e., Descriptive Statistics
      
      •	Android apps distribution per Category
      
      •	Ratings Analysis with respect to app type: benign or malware
      
      •	Apps with the number of ratings given

3.	Bivariate Analysis and Relationships with Label:

      •	Number of Dangerous permissions and Safe permissions with class labels.
      
      •	Number of ratings and the ratings with class labels.

4.	Data Preprocessing:

      •	Checking for Class Imbalance
      
      •	Feature Selection
      
      •	Categorical Variables Encoding

5.	Data Modeling:

       •	Random Forest
       
       •	Gradient Boosting
       
       •	Support Vector Machine
       
       •	K-Nearest Neighbors
       
       •	Naïve Bayes 

6.	Data Validation and Evaluation:
       
       •	Recall Score
       
       •	Precision Score
       
       •	Accuracy
       
       •	ROC-AUC Score

7.	Hyper-parameter Tuning:
      
      •	Grid Search CV

# Conclusion:

After doing all above-described steps we observed that:
Random Forest was overfitting the model.
Naïve Bayes was not working that well, maybe data doesn’t fit into its assumptions.
After Hyperparameter Tuning, Gradient Boosting Algorithm was giving the better results, with 84% recall, 89% precision and 83 % Accuracy. Thus, we created our final model with the maximum depth as 5 and n_estimators as 10. 
