
# Airflow-Project

Loan Review Workflow
Description

This project features an Apache Airflow DAG for evaluating loan applications. It generates random prediction scores for three loans, determining the best option based on these scores. The outcome is classified as "good" (score > 8) or "bad" (score ≤ 8), demonstrating Airflow's automation capabilities in decision-making workflows.


Features
Generates random scores for loan applications.
Evaluates and selects the best loan based on scores.
Uses Apache Airflow for orchestration of tasks.
Requirements
Python 3.x
Apache Airflow

Required Python packages: airflow, random

Installation
Clone the repository:


git clone https://github.com/jennIT20/Airflow-Project.git
cd Airflow-Project
Set up a Python environment and install dependencies:

pip install apache-airflow
Start the Airflow web server:


airflow webserver --port 8080
Start the Airflow scheduler in a new terminal:


airflow scheduler
Access the Airflow UI at http://localhost:8080.
