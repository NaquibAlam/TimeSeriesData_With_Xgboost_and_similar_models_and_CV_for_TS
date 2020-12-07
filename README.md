# TimeSeriesData_With_Xgboost_and_similar_models_and_CV_for_TS

## timeseriessplit-cv-strategy-for-ts-data.ipynb
1. This notebook explores how __TimeSeriesSplit__ CV strategy in __Sklearn__ can be used for hyper-parameter tuning.
2. We have tuned __C__ paramater of __LogisticRegression__ in __sklearn__.
3. The data for this notebook is available at https://www.kaggle.com/c/catch-me-if-you-can-intruder-detection-through-webpage-session-tracking2/data.


## simple-lgbm-groupkfold-cv.ipynb
1. This notebook explores how __GroupKFold__ CV strategy in __Sklearn__ can be used for hyper-parameter tuning for time-series data.
2. In this notebook we haven't done any hyper-parameter tuning though, __GroupKFold__ CV has just been used for validating the model's performance but the same methodology can be used for hyper-parameter tuning.
3. You can learn more about __GroupKFold__ CV and how it reduces the possibility of leakage with time-series CV from the __Markdown__ section of the notebook.
4. The data for this notebook are available at:
   * https://www.kaggle.com/ragnar123/m5-reduce-data
   * https://www.kaggle.com/c/m5-forecasting-accuracy/data
