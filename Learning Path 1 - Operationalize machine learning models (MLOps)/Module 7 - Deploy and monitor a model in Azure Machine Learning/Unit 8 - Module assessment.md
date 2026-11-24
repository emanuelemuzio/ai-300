# Assessment

*1.* A clinic's scheduling system needs an immediate no-show risk score the moment staff book an appointment. Which endpoint type should the team deploy the model to?

> Online endpoint

*2.* Why can Azure Machine Learning generate the scoring script and environment automatically when a data science team logs a model with MLflow?

> Because the MLflow model format stores metadata that Azure Machine Learning uses to build them during deployment

*3.* A team shifts 25% of endpoint traffic to a new model deployment. Its error rate rises sharply, while the previous deployment remains healthy. What should the team do first?

> Route all traffic back to the previous deployment, then investigate the new version

*4.* A team deploys and tests a model automatically, but wants a reviewer to approve it before the workflow shifts production traffic. What should the team configure?

> A protected GitHub production environment with a required reviewer

*5.* A model monitor reports a sustained prediction drift signal, and clinic staff confirm the flagged patients aren't actually high-risk. What's the most appropriate next step for the data science team?

> Investigate the signal and consider retraining the model on more recent data

## [[Unit 9 - Summary| Next Unit > Summary]]
