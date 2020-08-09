# docker-completo

- Docker Hub: https://hub.docker.com/u/hugodecastro

## Docker
É uma ferramenta que se apoia em recursos existentes no kernel, inicialmente Linux, para isolar
a execução de processos. As ferramentas que o Docker traz são basicamente uma camada de
administração de containers, baseado originalmente no LXC.

## Comandos utilizados
### Hello World!
```docker
docker container run hello-world # criação do primeiro container
```
### docker container
```docker
docker container create # criação do container
```
```docker
docker container start # inicialização do container
```
```docker
docker container exec -it # modo iterativo
```
```docker
docker container ls # lista containers ativos
```

### docker image
```docker
docker image pull nomedaimagem # baixa imagem do repositório
```
```docker
docker image ls # lista todas as imagens
```
```docker
docker image rm nomedaimagem # remove imagem
```
```docker
docker image tag # cria uma tag para a imagem
```
```docker
docker image build nomedaimgem # faz o build de uma imagem
```

## docker-compose
```docker
docker-compose up -d # inicializa o arquivo docker-compose.yml no modo daemon
```
```docker
docker-compose ps # lista os containers gerenciados pelo docker-compose
```
```docker
docker-compose exec nomedoserviço # modo iterativo
```
```docker
docker-compose down # para tpdps ps seviços gerenciados pelo docker-compose
```
