# Домашнее задание к занятию «ELK»

---

### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

### Решение 1.

![image](https://github.com/jinnonn/ELK-netology-hw/assets/146999555/d604b838-1c96-48f0-a948-65aca6fabfed)

---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

### Решение 2.

![image](https://github.com/jinnonn/ELK-netology-hw/assets/146999555/bbc81b65-b426-4bdb-a61d-3d3e830105f2)

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

### Решение 3.

![image](https://github.com/jinnonn/ELK-netology-hw/assets/146999555/733fbc5a-8e0c-4c77-9eca-0e22780532e4)

---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

### Решение 4.

![image](https://github.com/jinnonn/ELK-netology-hw/assets/146999555/cbf04d48-5429-48da-b969-3d0893a7c606)



*Приведите скриншот интерфейса Kibana, на котором будет виден этот лог и напишите лог какого приложения отправляется.*
