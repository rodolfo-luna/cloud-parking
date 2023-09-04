# cloud-parking
Desafio final do Bootcamp Spring boot da DIO

## Criando a database com DOcker

docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123 -d postgres:10-alpine

## Stop database

docker stop parking-db

## Start database

docker start parking-db
