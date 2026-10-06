# Real-Time Banking Fraud Detection & MLOps Pipeline

A streaming data pipeline that generates mock financial transactions, pushes them to an AWS RDS PostgreSQL database, and visualizes live metrics using Grafana.

## Architecture Flow
Python (Faker) ➔ AWS RDS PostgreSQL ➔ Grafana Dashboard

## Tech Stack
* **Python** (Pandas, Psycopg2, Faker)
* **Cloud Database:** AWS RDS PostgreSQL
* **Observability:** Grafana (Stat, Pie Chart, and Bar Chart panels)
* **Security:** Environment variables via `python-dotenv`
