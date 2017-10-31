
# Nginx and uwsgi 调优

### Nginx

* worker_processes  一般和cpu核数相等

* use epoll

```
events {
  use epoll;
  work_connections 5120;
}
```

### Nginx的upstream配置

