# Serviço de listagem de filmes

Esse projeto é um serviço de listagem de filmes. 

## Estrutura do projeto

Esse projeto trabalha com uma base de dados MongoDB e 

![Diagrama](./img/diagrama.png)

## Configuração

É preciso determinar a connection string pra que ele acesse o banco de dados MongoDB. Isso deve ser feito definindo a variável de ambiente MONGODB_URI

Exemplo:

MONGODB_URI: mongodb://mongouser:mongopwd@localhost:27017/admin

-----------------------------------------

# TESTES

<p>Para rodar este ambiente execute na pasta raiz</p>

<p>docker-compose up -d --remove-orphans --build</p>

<p>Para desmontar o ambiente execute</p>

<p>docker-compose down</p>

