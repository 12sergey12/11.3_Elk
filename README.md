# Домашнее задание к занятию 11.3. «ELK» Баранов Сергей


---

### Задание 1. Elasticsearch 

###### Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

![monitoring](https://github.com/12sergey12/11.3_Elk/blob/main/images/11.3-1_elasticsearch.png)


---


### Задание 2. Kibana

###### Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

![monitoring](https://github.com/12sergey12/11.3_Elk/blob/main/images/11.3-2_kibana.png)


---


### Задание 3. Logstash

###### Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

![monitoring](https://github.com/12sergey12/11.3_Elk/blob/main/images/11.3-3.png)


---

### Задание 4. Filebeat. 

###### Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

![monitoring](https://github.com/12sergey12/11.3_Elk/blob/main/images/11.3-4.png)
