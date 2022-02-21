
# Project Docker Todo List

Projeto que "conteineizei" as aplicações de frontend, backend e testes, criar uma conexão entre elas e orquestrar seu funcionamento! 🐋
## Etiquetas

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/eemr3/project-docker-todo-list)
![GitHub language count](https://img.shields.io/github/languages/count/eemr3/project-docker-todo-list)
![GitHub top language](https://img.shields.io/github/languages/top/eemr3/project-docker-todo-list)
[![GitHub issues](https://img.shields.io/github/issues/eemr3/project-docker-todo-list)](https://github.com/eemr3/project-docker-todo-list/issues)
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)


## Aprendizados

Entender o conceito de empacotamento de aplicações, assim como o conceito de escalonamento;
Entender o que é o Docker e qual problema ele se dispõe a resolver;
Entender o que é um processo Docker / container ;
Entender como instalar a ferramenta e executar um container ;
Entender quais são os principais comandos para utilização do Docker na interface de linha de comando (CLI);
Rodar imagens do Docker Hub (repositório oficial de imagens do Docker).
Criar imagens com Docker;
Entender a arquitetura de camadas ( layers ) das imagens Docker ;
Aplicar boas práticas e padrões na criação de imagem;
"Dockerizar"/Gerar contêineres para suas aplicações;
Gerenciar redes Docker , utilizando-as para a comunicação e isolamento de containers ;
Persistir dados dos containers utilizando volumes ;
Criar arquivos Compose para gerenciar todo seu ambiente com Docker ;
Gerenciar Services , Network e Volumes a partir do Compose .
## Screenshots

![App Screenshot](https://user-images.githubusercontent.com/42968718/154870176-5b7b76eb-1870-40bb-82ec-25a534e7b158.jpg)


## Stack utilizada

- **Front-end:** React, Node, React Hooks, Context Api. (Já veio construido)
- **Back-end:** NodeJs, Express, (Já vaeio contruido).
- **Container:** Docker, Docker Compose 
## Rodando localmente

Clone o projeto

```bash
  git clone https://link-para-o-projeto
```

Entre no diretório do projeto

```bash
  cd my-project/docker
```

Iniciando o container

```bash
  docker-compose up --build -d .
```

Acesse no navegador
```bash
  http://localhost:3000/
```
## Licença

[MIT](https://choosealicense.com/licenses/mit/)

