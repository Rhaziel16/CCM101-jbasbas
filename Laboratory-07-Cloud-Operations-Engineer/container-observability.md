# Container Observability

## 404 Error Log

```text
172.17.0.1 - - [05/Oct/2026:11:48:42 +0000] "GET /hidden-admin-page HTTP/1.1" 404 153 "-" "curl/8.5.0" "-"
```

## Why Application Logs Are Important

Application logs are important because they show what happened when an application has a problem. They help the administrator find the error and know which request caused it.

## Container Metrics

The `client-website` container was monitored using the `docker stats` command.

* CPU: **0.00%**
* Memory Usage: **2.734MiB / 1.859GiB**
