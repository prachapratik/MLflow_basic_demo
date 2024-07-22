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

export MLFLOW_TRACKING_PASSWORD=031fc2484ddc03206e529c787121cab7a2cdcd2b




```





