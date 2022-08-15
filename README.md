# nodejs-loadbalancer
loadbalancer nodejs with haproxy
```
docker build -t nodeapp .
```
Running
```
docker-compose up
```
Open in browser
```
localhost:8080

refresh browser, and port will change with round robin concept
```
Stop
```
docker-compose down
```
