# DRUPAL-HAPROXY-MONITORIZACI-N-Y-RECOLECCI-N-DE-M-TRICAS-Y-LOGS-JES-S-M-NDEZ-GARC-A
#1. Título: Sistema de monitoreo para Drupal y MariaDB
Se describe un sistema de monitoreo para un entorno compuesto por el CMS Drupal y la base de datos MariaDB.

#2. Balanceador de carga: HAProxy
Se utilizará HAProxy como balanceador de carga para distribuir el tráfico de la aplicación.

#3. Recolección de logs: Loki + Fluent Bit
Para la recolección de logs de Drupal, se utilizará la combinación de Loki y Fluent Bit. Los logs se podrán visualizar a través de Grafana.

#4. Monitorización: Docker-Compose, Prometheus y Node Exporter
El escenario será montado en Docker mediante Docker-Compose. La monitorización se realizará con Prometheus y Node Exporter, a través del uso de la herramienta Prometheus-Operator.

#5. Monitoreo de la Base de Datos: MySQL Exporter y Dashboard de Percona
Se utilizará MySQL Exporter para monitorear la base de datos. Para la visualización de los datos, se ha elegido el dashboard de Percona en Grafana.
