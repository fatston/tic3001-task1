# tic3001-task1
 task 1 for module idk
 
 
1.1
cd C:\repo\TIC3001\Task1\Task1A\app
docker build . -t clifton/node-web-app
docker images
docker run -p 3000:8080 -d --name node-web-app clifton/node-web-app
docker ps
docker logs 904

1.2
cd C:\repo\TIC3001\Task1\Task1A\nginx-sample
docker build -t clifton/nginx-reverse-proxy .
docker images
docker run -p 80:6969 -d --name nginx-reverse-proxy-container clifton/nginx-reverse-proxy
docker ps

1.3
cd C:\repo\TIC3001\Task1\Task1A
docker compose up  
