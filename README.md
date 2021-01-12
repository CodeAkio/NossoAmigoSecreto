![alt text](https://www.dropbox.com/s/js1wkzyl21vcyrh/logoapp2.png?raw=1) 
# Nosso Amigo Secreto

Project developed in Bootcamp OneBitCode

Realiza o sorteiro de amigo secreto, enviando o e-mail do sorteado para cada participante.

## Utilização

1. Instale o [Docker](https://docs.docker.com/engine/install/) e [Docker Compose](https://docs.docker.com/compose/install/).

2. Prepare o ambiente com o seguinte comando:
```console
docker-compose build
```

3. Certifique que as dependências estão instaladas:
```console
docker-compose run --rm app bundle exec bundle
```

4. Crie o banco de dados e rode as migrações:
```console
docker-compose run --rm app bundle exec rails db:create db:migrate 
```

5. Levante o serviço com o seguinte comando:
```console
docker-compose up
```

6. Agora acesse o a página em http://localhost:3000

7. Para ver os e-mails em ambiente de desenvolvimento acesse http://localhost:1080

## Executando testes

```console
docker-compose run --rm app bundle exec rspec
```
