#### The code shows you how to use DAG to automate the task of moving GCS data to BQ table.
---
1) Set the default location for the Cloud Composer: <br/>
```
gcloud config set composer/location asia-northeast1
```
2) Spin up a new Composer environment, which may take around 15 minutes: <br/>
```
gcloud composer environments create composer-demo
```
3) Upload the DAG (composer_demo.py) to the DAGs folder under environment configuration: <br/>
4) Check the DAG status under Airflow web UI: <br/>
