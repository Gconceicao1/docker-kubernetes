# docker-kubernetes
Repositório referente ao Lab de Docker e Kubernetes (IMPACTA)

A1 ---- 

## docker build -t mysql-image -f service\db\DockerFile .

## Inicia
docker run -d --rm --name mysql-container mysql-image


## Acessa o Container
docker exec -it mysql-container /bin/bash

##  Acessar o Mysql
mysql -uroot -p gabs

## Rodar o script de banco de dados (utilizar o powershell para executar o script, não utilizar o mesmo prompt dos ultimos comandos)
docker exec -i mysql-container mysql -uroot -p gabs < services/db/script.sql



-------
