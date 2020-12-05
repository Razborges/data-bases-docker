# DataBases in Docker
Coleção de docker para alguns dos dbs mais utilizados para uso em desenvolvimento local

## Lista de Dockers:

- DynamoDB
- ElasticSearch
- MariaDB
- MongoDB
- MySQL
- Postgres

## Como Utilizar:

Aqui está uma sugestão de _docker-compose.yml_ para rodar esses databases localmente, você pode inclusive combinar mais de um para uso.

A grande maioria já está configurado com volume local para não acontecer perda de dados, caso não precise basta não adicionar esta linha.

Alguns possuem já no _docker-compose.yml_ um administrador de consulta ao bd, caso prefira usar outro basta não utilizá-los.

Para configurar login e senha do container basta alterar as propriedades no database desejado (para aqueles que possuem).

## Como Contribuir:

Clone este repositório, faça as sugestões que acha pertinente e abra um Pull Request para que seja testado e avaliado.
