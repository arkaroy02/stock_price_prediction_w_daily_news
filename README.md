The goal of this project is to see, if incorporating news price can improve the prediction.
For this, I have collected daily news from 2008-2016 which is available in kaggle and collected corresponding price. volume of the DJIA.
We have seen an improvement in prediction when we added the BERT sentiment scores along with the last 7 days price.

r2_score
vader	           0.680813
textblob	       0.867332
bert	           0.885703
bert_tuned	     0.854689
normal	         0.835450
