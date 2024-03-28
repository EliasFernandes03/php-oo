# SETUP PHP

Uma base de aplicação limpa (sem frameworks), para estudos em PHP Orientado a objetos.

Essa estrutura já está dockerizada, então basta ter o docker compose rodando em seu computador que é pra dar tudo certo.

## Tecnologias

- PHP 8.3
- MySQL
- nginx

## Como usar

Primeiro basta clonar o repositório

`git clone bla bla bla`

Agora entre na pasta com o terminal 
`cd php-oo`

E agora basta rodar o docker

`docker rm setup-php -f`
`docker rm setup-nginx -f`
`docker rm setup-mysql -f`

`docker-compose up -d`

Pronto,é sucesso!

Acesse o http://localhost:8080
