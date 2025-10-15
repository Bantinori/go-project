WIP Project for live telemetry w/ reporting on certain devices identified by a network scan, and verified by an API call. To be pushed onto a RaspberryPi.

TECH STACK (That I know of currently)
GO (core)
Bash (automation)
SQL (MySQL or MariaDB, something lite and easy)
Prometheus
Grafana
MySQL
cAdviser
Node Exporter
RaspberryPi
  Docker
  Portainer
  

WHAT TO BUILD

( ) Internal Network Scanner
( ) Parse and ID appropriate devices
( ) Implement API client
( ) Build MySQL Database
( ) Collect telemetry data, store it (MySQL DB and Prometheus), and automate this process
( ) Build Grafana dashboards using Prometheus as the datasource
( ) Create reports using views in DB, automate sending reports to users via email using Bash and cron jobs.
( ) Add anomaly detection (recognizing bad telemetry (Needs to have a base set of "normal" telemetry))
( ) Package for deployment
( ) Something for sending commands to systems remotely...
