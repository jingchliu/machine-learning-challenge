# machine-learning-challenge
SVM Model Results:
                precision    recall  f1-score   support

     CONFIRMED       0.42      0.45      0.43       411
FALSE POSITIVE       0.61      0.64      0.62       484
     CANDIDATE       0.85      0.79      0.82       853

     micro avg       0.67      0.67      0.67      1748
     macro avg       0.63      0.63      0.63      1748
  weighted avg       0.68      0.67      0.67      1748
   samples avg       0.67      0.67      0.67      1748
   
Neutral Network Results:
                precision    recall  f1-score   support

     CONFIRMED       0.48      0.42      0.45       411
FALSE POSITIVE       0.67      0.72      0.69       484
     CANDIDATE       0.84      0.85      0.85       853

     micro avg       0.71      0.71      0.71      1748
     macro avg       0.66      0.66      0.66      1748
  weighted avg       0.71      0.71      0.71      1748
   samples avg       0.71      0.71      0.71      1748
   
Neutral Network's f1 scores are slightly higher than that of the SVM scores but very close. It might be because I did more hypertuning in the Neutral Network model such as the Optimization Algorithm and Batch Size and Number of Epochs. The nuetal network model also has a deep learning step that might help. The result could be improved in the SVM if I also try hypertune the SVC kernal type.