# RETRO BOARD

----
2. Download the dependencies
```bash  
 go get -t -v -d ./…  
```
---
### DB setup
1. Set-up mysql docker container
```bash
docker run --name retro-board -e MYSQL_ROOT_PASSWORD=password -e MYSQL_DATABASE=retro-board -p 2001:3306 -d mysql:8.0.31
```


---
### Run application
```bash  
go run main.go
```
