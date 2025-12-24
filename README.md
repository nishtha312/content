data-engineering-capstone/
│
├── ingestion/
│   ├── api_ingestion.py
│   ├── db_ingestion.py
│   └── kafka_producer.py
│
├── airflow/
│   ├── dags/
│   │   └── data_pipeline_dag.py
│
├── transformation/
│   ├── spark_jobs/
│   │   └── transform_data.py
│   └── dbt/
│       ├── models/
│       └── tests/
│
├── warehouse/
│   └── schema_design.sql
│
├── data_quality/
│   └── great_expectations/
│
├── deployment/
│   ├── Dockerfile
│   └── docker-compose.yml
│
├── terraform/
│   └── main.tf
│
├── ci-cd/
│   └── github-actions.yml
│
├── README.md
