# docker启动Prometheus服务



```sh
docker run -d -p 9090:9090 -v D:\IdeaProjects\monitor\prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus --config.file=/etc/prometheus/prometheus.yml
```

# Grafana可视化

```sh
docker run -d -p 3000:3000 grafana/grafana
```

+ Add data source 
  + url使用ip，localhost，127.0.0.1访问不通





参考地址：

[使用 Prometheus 和 Grafana 监控 Spring Boot 应用](https://www.codenong.com/cs106159086/)

[Actuator + Prometheus + Grafana搭建微服务监控平台](https://cloud.tencent.com/developer/article/1702326)

