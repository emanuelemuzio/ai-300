# Assessment

*1.* A data scientist wants to run a script as a command job to train a PyTorch model, setting the batch size and learning rate hyperparameters to specified values each time the job runs. What should be done by the data scientist?

> Add arguments for batch size and learning rate to the script, and set them in the command property of the command job.

*2.* A data scientist has trained a model in a notebook. The model should be retrained every week on new data. What should the data scientist do to make the code production-ready?

> Convert the code to multiple functions in a script that read the data and train the model.

*3.* A data scientist trains a regression model and wants to track the model's performance by storing the Root Mean Squared Error (RMSE) with the experiment run. Which method can be used to log the RMSE?

> `mlflow.log_metric()`

*4.* When a data scientist enables MLflow autologging, where can all model assets be found?

> In the model folder under **Outputs + logs**.

## [[Unit 9 - Summary| Next Unit > Summary]]
