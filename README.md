# DRUPAL-HAPROXY-MONITORIZACI-N-Y-RECOLECCI-N-DE-M-TRICAS-Y-LOGS-JES-S-M-NDEZ-GARC-A
# Se describe un sistema de monitoreo para un escenario compuesto por un CMS Drupal y una base de datos MariaDB.
#  Se utilizará HAProxy como balanceador de carga, Loki + Fluent Bit para la recolección de logs, y Grafana para la visualización de los mismos. 
#    La monitorización se realizará mediante Docker-Compose, Prometheus + Node Exporter, y la herramienta Prometheus-Operator.
#      También se utilizará MySQL Exporter para monitorear la base de datos y el dashboard de Percona en Grafana.
