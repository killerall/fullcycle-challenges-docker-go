## Repositorio do desafio 1 de Go
    Repositorio do desafio de GO com docker com full-cycle

    Basicamente um deploy de uma messagem no console, otimizando a imagem final.

## Build
docker build -t rodrigoantonio/codeeducation . -f./devops/Dockerfile

## Publish
docker push rodrigoantonio/codeeducation

## Run 
docker run  --rm rodrigoantonio/codeeducation
