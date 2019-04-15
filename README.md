# forex-binary-option-prediction
Predict AUD/JPY for iqoption binary forex. The ultimate goal will be predicting any forex but AUD/JPY is picked due to its stability of price.

Data is from `https://www.histdata.com/download-free-forex-data/?/ascii/1-minute-bar-quotes`.<br>Run `convert_est_to_target_time.py` to convert EST to your own timezone.

## Results
SVM and GBC performed horribly while (not well tuned) LSTM looks promising (0.5017174381379991 accuracy):
![plot](lstm_result.png)
