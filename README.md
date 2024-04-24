
#                              **Project**

---




**Name- Shubham Kamboj**




---





# **Red Wine Quality Prediction- EDA + Classification using 5 different methods**

**Is quality in wine subjective or objective?**

Read this very interesting wine blog https://wineandotherstories.com/the-six-attributes-of-quality-in-wine/ where the author poses the question of "Do I like the wine?" implying a personal preference vs "Is it a good wine?" implying quality as an objective factor of measurement. Dataset source: https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009



**Explanation of the variables**

**Fixed Acidity:** most acids involved with wine or fixed or nonvolatile (do not evaporate readily).

**Volatile Acidity:** the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste.

**Citric Acid:** found in small quantities, citric acid can add 'freshness' and flavor to wines.

**Residual Sugar:** the amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter.

**Chlorides:** the amount of salt in the wine.

**Free Sulfur Dioxide:** the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion.

**Total Sulfur Dioxide:** amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2.

**Density:** the density of water is close to that of water depending on the percent alcohol and sugar content.

**pH:** describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4.

**Sulphates:** a wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial.

**Alcohol:** this is the percent alcohol content of the wine.

**Quality:** output variable (based on sensory data, score between 3 and 8).





# **Final Comparision & Conclusion**


Based on the above results, the Gradient Boosting Machines model performs the best with the highest validation score (0.8737) and the lowest mean absolute error (0.1263). It also has a high training score and a relatively high cross-validation score, indicating good generalization.

The Random Forest model also performs well with a validation score of 0.8211 and a low mean absolute error of 0.1789. It has a perfect training score but a slightly lower cross-validation score compared to Gradient Boosting Machines.

Logistic Regression, Decision Tree, and Support Vector Machines show lower performance compared to the other two models. They have lower validation scores and higher mean absolute errors. However, it's worth noting that Logistic Regression and Decision Tree models may have convergence issues, as indicated by the convergence warnings.

**Overall, based on the current results, the Gradient Boosting Machines model is recommended for its high accuracy and low error rate, making it a robust choice for predicting the quality of red wine in this dataset.**
