# *MANUAL DE SUPERVIVENCIA:*

**#1. Título:** Balanceo de carga de drupals con HaProxy y monitorización de logs de ambos drupal + monitorización de métricas con Grafana (host & BBDD). 

**#2. Balanceador de carga: HAProxy:** Se utilizará HAProxy como balanceador de carga para distribuir el tráfico de los CMS, posibilidad de escalado de los mismos a cuantos nuestro equipo esté dispuesta a correr.

**#3. Recolección de logs: Loki + Fluent Bit:** Para la recolección de logs de Drupal, se utilizará la combinación de Loki y fluentd. Logs visualizables a través de Grafana.

**#4. Monitorización: Docker-Compose, Prometheus y Node Exporter:** Escenario será montado en Docker mediante Docker-Compose. La monitorización se realizará con Prometheus y Node Exporter, a través del uso de la herramienta Prometheus-Operator, monitorizamos nuestro host. (Monitorización ideal para servers).

**#5. Monitorización: DMonitoreo de la Base de Datos: MySQL Exporter y Dashboard de Percona para Grafana:** Se utilizará MySQL Exporter para monitorear la base de datos. 

**SISTEMA DE ALERTAS VIA MAIL AGREGADO**


