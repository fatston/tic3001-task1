# tic3001-task1
 task 1 for module idk
 
 
1.1<br />
cd C:\repo\TIC3001\Task1\Task1A\app<br />
docker build . -t clifton/node-web-app<br />
docker images<br />
docker run -p 3000:8080 -d --name node-web-app clifton/node-web-app<br />
docker ps<br />
docker logs 904<br />

1.2<br />
cd C:\repo\TIC3001\Task1\Task1A\nginx-sample<br />
docker build -t clifton/nginx-reverse-proxy .<br />
docker images<br />
docker run -p 80:6969 -d --name nginx-reverse-proxy-container clifton/nginx-reverse-proxy<br />
docker ps<br />

1.3<br />
cd C:\repo\TIC3001\Task1\Task1A<br />
docker compose up  <br />
