# What’s the Index? Using the Global Database of Events, Language, and Tone (GDELT) in predicting the Philippine Stock Exchange Index (PSEi)
by Nika Espiritu, Matthew Maulion, Jasper Pangan, Vincent Rivera

Investors, economists, and other actors in the financial sector closely watch the Philippine Stock Exchange Index (PSEi). For investors, they would usually use turn to financial theories to decide when to buy or sell stocks, but they are also affected by the news and their sentiments on the business climate. This paper sought to predict the percent change in the PSEi to using data from the Global Database of Events, Language and Tone (GDELT). Creating a Dask cluster was needed to wrangle the hefty GDELT. After data preprocessing and conducting an exploratory data analysis, machine learning models such as Gradient Boosting Method (GBM) and XGBoost (XGB) were experimented to find the optimum model. Three prediction analyses were perfromed: 1) Intraday; 2) 1-day ahead; and 3) 3-day ahead. Consistently, the GBM model provided the lowest Mean Absolute Errors (MAE) of 0.008 for Intrady, 0.008 for 1-day ahead, and 0.013 3-day ahead respectively. Using the optimal model for each prediction analysis, feature importance was employed. This revealed that the Previous PSEi Closing Price, Goldstein score, and Tone were identified as important features for the various models.
