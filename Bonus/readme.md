label:	0 hate speech
	1 offensive language
	2 neither 
train.csv: 19827 instances
test.csv: 4958 instances 

As a reference, the results of DistilBERT:

             	precision    recall  f1-score   support

        hate       0.56      0.28      0.37       294
   offensive       0.94      0.96      0.95      3821
     neither       0.87      0.93      0.90       842

    accuracy                           0.91      4957
   macro avg       0.79      0.72      0.74      4957
weighted avg       0.90      0.91      0.91      4957

