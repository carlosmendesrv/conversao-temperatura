[![](https://kubedev.io/wp-content/uploads/2020/08/Artboard-1@2x.png)](https://kubedev.io/wp-content/uploads/2020/08/Artboard-1@2x.png)

## Desafio KubeDev
Seguindo a aula, cria o seu repositório no GitHub baseado no projeto conversão temperatura (https://github.com/KubeDev/conversao-temperatura) e cria uma imagem Docker da aplicação e executa na sua máquina e me manda o seu repositório pra ver se tá tudo certo (não esquece de seguir as melhores práticas).


## Requisitos 

- Docker

## Executando o projeto

Executando o projeto
```bash
git clone https://github.com/carlosmendesrv/conversao-temperatura.git
```

```
docker build -t carlosmendesrv/conversao-temperatura:v1 .
docker run -d -p 8080:8080 --name conversao-temperatura carlosmendesrv/conversao-temperatura

```
O projeto estará disponível na seguinte url http://127.0.0.1:8080

## Executando imagem do projeto 
Executando o projeto, pela imagem hospedada no docker hub.

```
docker run -d -p 8080:8080 --name conversao-temperatura carlosmendesrv/conversao-temperatura:latest
```

O projeto estará disponível na seguinte url http://127.0.0.1:8080