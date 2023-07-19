# Real Estate Sales Price Prediction

  Project status: Active.

# Project objective
This project is based on a famous Kaggle competition of House prices in Ames, Iowa (USA). The goal is to test different approaches of ensemble decision-threes algorithms, transformations, and preprocessing tasks to maximize the model performance and training. <br>

<center> <img src='https://github.com/Melo97/Real-Estate-Sales-Price-Regression-Using-RF-and-XGBoost/blob/main/housesbanner.png?raw=true'> </center>

# Technologies 
  
  **List of technologies**:
  <div style="display: inline_block"><br>
  <img align="center" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg">
  <img align="center" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">
  <img align="center" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg">
  <img align="center" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original-wordmark.svg"> 
    
</div>

  - **Visual Representations**: matplotlib/seaborn <br>
  - **Machine Learning**: scikit-learn

# Steps

To summarize, I was able to make an accurate model predicting house prices in Ames, Iowa, by doing the following:

- **Explanatory Data Analysis**: Helped me to understand feature relationships and how they interact with the response variable. Also, it was necessary to validate hypothesis and make inferences.
- **Feature Engineering**: Selecting the right features is never easy, but here it managed to organize the data to provide the best for the models. First, organizing categorical columns, and then selecting the numerical from a correlation matrix. 
- **Preprocessing**: Imputation and Encoding strongly impacted the model's performance.
- **logarithmic transformation**: The output data had a strong dispersion from the normal distribution on its tails. By log-transforming it, we were able to reach much better regression lines.
- **Model selection**: By applying different machine learning models, we could compare which would yield better results, even combining them.

# Methods

To train the model, tree ensemble methods were tested to see which one gives the lowest percentual mean absolute error:
- Random Forests Regressor;
- Extreme Gradient Boosting Regressor;
- RF and xgboost regressors Stacked;

It was defined that a predictor was good if its score was below 10% variation VS the real value. All tree methods achieved the mark, with the 2nd model having he best performance, and the 1st the best training time.

# Conclusion

The model with the highest performance was the Extreme Gradient Boosting, although it is not significantly higher than the Random Forest (Bagging), and takes longer to train. If the model is to be retrained on a larger dataset, the last one would make more sense to be used and deployed. On the other hand, if the new dataset is smaller, the first one is encouraged to be used.  
  
# Contact
<div> 
  <a href="https://www.linkedin.com/in/daniel-iglesias-melo/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
 	<a href="https://wa.me/5581989017459" target="_blank"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank"></a>
 <a href= https://discordapp.com/channels/@me/1119691506735906826/" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a> 
  <a href = "mailto:daniel.iglesiascm@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=red" target="_blank"></a>
  
</div>
