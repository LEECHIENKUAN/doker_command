# 列出目前 images 
```
docker images 
```

# 刪除 images 
```
docker rm <someone_image_id> 
```

# 列出目前的所有 Container 
```
docker ps -a 
```

# 刪除 Container 
```
docker rmi <someone_container_id> 
```

# docker container restart 
reload the NGINX configuration run the command
```
docker kill -s HUP container_name

```

# docker reload nginx 
```
docker exec <nginx_container_id> nginx -s reload
```

# 

# 參考網址
https://docs.docker.com/engine/reference/commandline/ps/
