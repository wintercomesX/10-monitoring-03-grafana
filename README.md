# Домашнее задание к занятию 14 «Средство визуализации Grafana» Кандала Кирилл
## Задание 1

![grafana dash](https://github.com/wintercomesX/10-monitoring-03-grafana/blob/main/grafana1.PNG)

## Задание 2
### Список запросов к prometheus
1. 100 - avg(irate(node_cpu_seconds_total{mode="idle"}[5m])) * 100
2. node_load1
3. node_load5
4. node_load15
5. node_memory_MemAvailable_bytes / 1024 / 1024
6. (node_filesystem_size_bytes - node_filesystem_free_bytes) / node_filesystem_size_bytes * 100

### Скриншот дашборда

![grafana dash](https://github.com/wintercomesX/10-monitoring-03-grafana/blob/main/grafana3.PNG) 

## Задание 3

![grafana dash](https://github.com/wintercomesX/10-monitoring-03-grafana/blob/main/grafana4.PNG) 
