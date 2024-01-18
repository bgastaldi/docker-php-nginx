# docker-php-nginx
Docker + PHP (8.3.1) + Nginx (Único Container) 

1 - ``` docker build --no-cache -t bgastaldi/myapp:latest . ```

2 - ``` docker run -p 8081:80 --name myapp bgastaldi/myapp ```

3 - Check ```http://localhost:8081```
