
# Machine Learning based Movie Recommendation System

Movies and webseries data is one of today's popular datasets
for OTT Recommendation. Dataset contains multiples columns 
like title, userID, year, kind, genre, vote, country, language,
cast, director, composer, writter, runtime, of rating as the attributes 
for recommendation.

This prediction is a part of  Ctrl Shift Intelligence,
the Machine Learning event of COPS Week 2022, 
 organized by Club of Programmers IIT(BHU) Varanasi.

19th April 2022 to 21th April 2022
## 🔗 Links
[kaggle competion link here](https://www.kaggle.com/competitions/ctrl-shift-intelligence-2k22/overview)

Username : Noob:)

## Techniques Used

- Data Exploration using Seaborn kde plot, Pearson Correlation
- Handled Null Values using random imputation
- Feature Engineering : transformed features such as genre and title
- Used Mutual Information for selection of important categories, where features had large number of categories
- Features such as cast, director, writter and composer were discarded as they had very large number of categories, with very less frequency and low mutual information, hence not very helpful in predictons
- K fold Cross Validation was used
- Catboost was used as predictive model and was hypertuned


As a result I secured #1st Position in this competition 

