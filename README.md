## Informações  sobre o exercício "Processo de CI" (04/08/2020)

Exercício realizado conforme instruções abaixo:<br /><br />

1) Você deverá pegar sua aplicação Laravel das fases anteriores e adicioná-la em um pipeline de integração contínua utilizando o Google Cloud Build, para isso terá que:<br /><br />

Gerar a imagem do docker-compose e fazer o push no seu Container Registry do GCP. <br />
Criar uma trigger para ser disparada todas as vezes que um commit entrar no repositório do Github.<br />
Os steps do Google Cloud Build deverão ser:<br />
Executar o docker-compose<br />
Executar o composer<br />
Copiar o arquivo .env.example para .env<br />
Rodar um artisan key:generate<br />
Executar as migrações<br />
Executar os testes utilizando o PHPUnit<br /> <br />

2) Você deverá instalar a App do Google Cloud Build disponível no Market Place do Github. Crie um branch develop em seu repositório. Todas as vezes que uma pull request for criada, imediatamente o Google Cloud Build deverá iniciar o processo de CI.<br /><br />

## Informações sobre exercício "Desafio Docker" (22/07/2020)

**Tarefa 1**: Foi atualizado a imagem nginx conforme solicitado no exercicio.<br />
Aualizados arquivos Dockerfile e nginx.conf da pasta ./docker/nginx e Docker-compose.yaml.<br />
Criado arquivo entrypoint.sh dentro da pasta .docker/nginx.<br />
Github Atualizado.

**Tarefa 2**: Imagem atualizada no docker hub: https://hub.docker.com/repository/docker/fabianoteixeirasilva/codeeducation<br />
Código fonte em .docker/golang.<br />

## Informações sobre exercício "Publicando imagem laravel" (20/07/2020)

Abaixo, o endereço da imagem no Docker Hub do exercício:
https://hub.docker.com/r/fabianoteixeirasilva/laravel_app


<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>
