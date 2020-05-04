# voice_gender_svm_python
Data source: https://www.kaggle.com/primaryobjects/voicegender#voice.csv
Objectives: classify gender by voice features using SVM (Support Vector Machine)

Data Preprocessing:
  1. Detect missing values deal with it if any (There is no missing value in this dataset.)
  2. Scale features
Split dataset into training (60%) and test set (40%)
Fit training set into model -SVM (linear)
Check performance of model
  Accuracy is about 0.9140
  Cross validation with 5 and the mean score is about 0.9173

Conclusion: SVM provides good accuracy on this dataset which means it predicts well.
