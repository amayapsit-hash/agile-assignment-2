# End-to-End DevOps Pipeline Architecture

## Application
Iris ML Classification Application

## Workflow

1. Jira – Agile planning, backlog management,
   sprint planning and task tracking.
2. GitHub – Source code version control and commits.
3. GitHub Actions – Automatically runs tests and
   builds the Docker image when code is pushed.
4. Docker Compose – Runs the application services.
5. Flask API – Serves Iris classification predictions.
6. MLflow – Tracks ML experiments, parameters,
   metrics and model versions.
7. Prometheus – Collects application metrics.
8. Grafana – Visualizes metrics through dashboards.

## End-to-End Flow

Jira → GitHub → GitHub Actions → Docker Compose
→ Flask API and MLflow → Prometheus → Grafana

Monitoring results can be used to create improvement
tasks in the Jira backlog.
