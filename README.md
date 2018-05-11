# Predicting if a Kiva Loan Posting Will Expire (Not Funded)
## Authors: Dylan Connor, Kaung M. Khin

**Abstract**: Kiva is a non-profit organization that organizes and facilitates micro-funding to support various entrepreneurial efforts across the world. While the vast majority of loan postings do get funded, we focus on the loans that goes unfunded (expired). The challenge in identifying which loans will not get funded mainly stems from the highly imbalanced nature of the data set (579,934 funded vs 38,879 unfunded). Nevertheless, we were able to employ data-balancing techniques such as SMOTE and ADASYN to accurately predict the true-positives (unfunded posts) well. Through our efforts in feature engineering, data balancing and optimizing our classifiers, we were able to achieve an AUC ROC score of 0.94. We believe that our work will be helpful for Kiva to target their efforts on the small minority of loans that might need the extra "push" to get funded as this usually means a life changing opportunity for the loan requestors. 

The final paper for this project can be found [here](https://github.com/damitkwr/KivaExpiry/blob/master/ConnorKhinTeam22-FinalPaper.pdf).

The presentation of our results can be found [here](https://github.com/damitkwr/KivaExpiry/blob/master/Kiva_Presentation.pdf).

The iPython Notebooks for this project are organized as follows:
- [Data Wrangling](https://github.com/damitkwr/KivaExpiry/blob/master/01%20-%20Data%20Wrangling.ipynb)
- [ML Analysis](https://github.com/damitkwr/KivaExpiry/blob/master/02%20-%20Primary%20ML%20Analysis.ipynb)
- [Visualization of results](https://github.com/damitkwr/KivaExpiry/blob/master/03%20-%20Variable%20Status%20Graphs.ipynb)
