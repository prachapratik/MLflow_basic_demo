# MLflow_basic_demo


https://dagshub.com/prachapratik/MLflow_basic_demo.mlflow

import dagshub
dagshub.init(repo_owner='prachapratik', repo_name='MLflow_basic_demo', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/prachapratik/MLflow_basic_demo.mlflow


export MLFLOW_TRACKING_USERNAME=prachapratik

# export MLFLOW_TRACKING_PASSWORD=6824692c47a369aa6f9eac5b10041d5c8edbcef0


```





