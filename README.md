## Aplicação laravel para executar container criado no DockerHub

https://hub.docker.com/repository/docker/lucasfbr/laravelapp

- Baixar a imagem do dockerhub: docker pull lucasfbr/laravelapp:1.0.0
- Fazer o clone do projeto laravel git: https://github.com/lucasfbr/DesafioFullCycle.git
- Executar com o comando: docker compose up -d
- Abrir o navegador: 'http://localhost:8000/'

Versão com script de entrypoint executando composer install, migrations, key:generate

## Atualização

## Host e porta nginx podem ser definidas no docker-compose

- Executar comando: docker-compose up -d
- Para mudar o host ou a porta, deve editar no arquivo docker-compose.yaml

## Variaveis definidas

- NGINX_HOST=app
- NGINX_PORT=9000 
