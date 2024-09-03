# Домашнее задание к занятию "`ELK`" - `Репин Андрей`


---

### Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

![скриншот ](https://github.com/RepinAndrey/ELK/blob/main/img/elk1.png)

### Задание 2 Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

![скриншот ](https://github.com/RepinAndrey/ELK/blob/main/img/elk2.png)

### Задание 3
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

![скриншот ](https://github.com/RepinAndrey/ELK/blob/main/img/elk3.png)

### Задание 4 Filebeat
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

![скриншот ](https://github.com/RepinAndrey/ELK/blob/main/img/elk4.png)
