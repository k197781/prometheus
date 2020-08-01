## Start
### start monitored server
start http server
```
cd http
go run main.go
```

### start monitoring server
start prometheus and grafana
```
make run
```

## Grafana
### user
initial user and password
```
admin/admin
```

### configuration
Data Sources > Prometheus
```
url: http://appname_prometheus_1:9090  // set container name
```