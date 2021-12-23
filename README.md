# machine_learning_training_bot
algorithmic trading bot with SVM learning functionality and model classification reporting


## baseline performance:
the deviation between actual and modeled returns in the chart below indicates poor efficacy of the baseline model

<img src="baseline_model.png" width="400"/>


## SVC model
support vector classification vastly improves the fit, indicating a more causal relationship found between the training and testing data

<img src="svc_model.PNG" width="400"/>


## tuning the baseline model
tightening the training window and tweaking the SMA inputs resulted in some improvement but the model is still only showing predictive strength through limited slices of the time series

<img src="tuning_baseline_model.PNG" width="400"/>
