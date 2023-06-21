# *MANUAL DE SUPERVIVENCIA:*

**#1. Título:** Balanceo de carga de drupals con HaProxy y monitorización de logs de ambos drupal + monitorización de métricas con Grafana (host & BBDD). 

**#2. Balanceador de carga: HAProxy:** Se utilizará HAProxy como balanceador de carga para distribuir el tráfico de los CMS, posibilidad de escalado de los mismos a cuantos nuestro equipo esté dispuesta a correr.

**#3. Recolección de logs: Loki + Fluent Bit:** Para la recolección de logs de Drupal, se utilizará la combinación de Loki y fluentd. Logs visualizables a través de Grafana.

**#4. Monitorización: Prometheus y Node Exporter:** La monitorización se realizará con Prometheus y Node Exporter, monitorizamos nuestro host. (Monitorización ideal para servers). Dashboard usado: Node Exporter Full (Linux).

**#5. Monitorización: Monitoreo de la Base de Datos: MySQL Exporter**: La monitorización se realizará con Loki y Mysql Exporter, monitorizamos nuestra BBDD Dashboard usado: Percona, adaptable a MySQL, MongoDB. Incluye buffers como InmoDB...

**SISTEMA DE ALERTAS VIA MAIL AGREGADO**


