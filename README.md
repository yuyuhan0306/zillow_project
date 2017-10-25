# zillow_project
We participated in the Zillow Kaggle competition in August 2017, with the goal of improving Zillow's Zestimate home pricing algorithm by using machine learning techniques to predict error between Zestimates and actual sale prices in the greater Los Angeles area.

Kaggle link: https://www.kaggle.com/c/zillow-prize-1

We implemented a workflow with four major components: exploratory data analysis (EDA), handling missingness, feature engineering, and modeling. For modeling part, we fitted multiple linear regression, ridge regression, lasso regression, random forest, and gradient boosting machines models. There are some interesting insights:

(1) Given the amount of missing data and relatively large number of features in this project, imputation strategy and feature engineering were very important with respect to reducing prediction error. 

(2) Using a simple imputation strategy was the most significant factor to improving our results.

(3) As for tuning hyperparameters, we figured out that  a smaller shrinkage with a higher tree count improved score. Yet, a higher shrinkage with higher tree count hurt score. Additionally, the smallest shrinkage did not produce optimal results.

(4) Random forest produced the best results for us.

(5) Agile machine learning allowed us to run models more effectively and efficiently.

If you would love to learn more about our workflow, concepts, insights, and machine learning theories, please feel free to take a look at our blog post. https://blog.nycdatascience.com/student-works/zillow-zestimate-kaggle-competition/

Slides:
https://docs.google.com/presentation/d/1UH8ZpwLY63fw3oq38yEGfUxnWY5epKeP3WgwSzkgAwU/edit?usp=sharing
