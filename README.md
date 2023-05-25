# Project Information:
Android is the most popular operating system in the world, with over 2.5 billion active users spanning over 190 countries. Created by Andy Rubin, it quickly became the favorite OS for most of the mobile manufacturers in the early 2010’s. Being favorite of so many users, the statistics of having highest malware rate i.e., 47.15% of all vulnerable devices is a concern for android mobile users. 
	In this project,I develop a model using machine learning techniques that can differentiate between the malware apps and the benign ones.
  
# Problem Statement: 
The dataset consists of nearly 30,000 apps from various sources: Google's play store, hiapk, app China, Android, mumayi, gfan slideme, and pandaapp along with the extracted permissions with the package. 

The main objective is to find on the basis of these features what apps are the problem creators for the Android users.

# Evaluation Metric:
To maximize our malware detection accuracy...alongwith avoiding benign classified as malware since that could put ethical question on the concerned app.

Emphasized metric are: Recall and Precision

# Approach to the modelling process:
1. The features were not in linear relationship with the class variable, we didn’t go for Logistic Regression
2. Price was a great distinguisher between the classes. So, I decided to not to use Decision Tree Classifier.
3. Decided to go with other tree based classifiers like Random Forest, Gradient Boosting since they work on the principle of ensemble.
4. Other classifier models used are SVM, Naïve Bayes and KNN


# Conclusion:

1. Random Forest was overfitting the model.
2. Naïve Bayes was not working that well, reason being naive assumption of features being statristically independent, which was not in this case.
3. After Hyperparameter Tuning, Gradient Boosting Algorithm was giving the better results, with 84% recall, 89% precision and 83 % Accuracy. Thus, we created our final model with the maximum depth as 5 and n_estimators as 10. 
