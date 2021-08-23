# docker启动Prometheus服务



```sh
docker run -d -p 9090:9090 -v D:\IdeaProjects\monitor\prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus --config.file=/etc/prometheus/prometheus.yml
```

# Grafana可视化

```sh
docker run -d -p 3000:3000 grafana/grafana
```

+ Add data source 
  + url使用ip，localhost访问不通

