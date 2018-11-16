#### The code shows how to use Cloud Composer DAG to automate the task of importing a csv file from a GCS bucket to a BigQuery table, run a query, and save the result to another BigQuery table.
---
1) Set the default location for the Cloud Composer: <br/>
```
gcloud config set composer/location asia-northeast1
```
2) Spin up a new Composer environment, which may take around 15 minutes: <br/>
```
gcloud composer environments create composer-demo
```
3) Upload the DAG file (composer_demo.py) to the DAGs folder. <br/>
4) Check the DAG status under Airflow webserver. <br/>
