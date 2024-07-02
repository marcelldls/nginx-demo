# nginx-demo
```
podman run -v $(pwd)/html:/html -v $(pwd)/nginx.conf:/etc/nginx/nginx.conf -p 8080:8080 -d nginx
```