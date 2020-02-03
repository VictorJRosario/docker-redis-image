# Docker And Kubernetes - Udemy

## Redis Image
To create a Redis Image:
```
FROM alpine
RUN apk add --update redis
CMD ["redis-server"]
```