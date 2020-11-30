Este é o repositório principal contendo docker-compose.yml para desenvolvimento local e os submódulos backend/frontend da aplicação.
<p align="center">
<!--   <img src="https://github.com/bprofiro/gofinances/blob/master/frontend/src/assets/logo.svg" /> -->
</p>

<p align="center">
<!--   <img src="https://github.com/bprofiro/assets/blob/master/In%C3%ADcio.png" /> -->
</p>

## Sobre o Projeto

  Esse projeto foi desenvolvido durante o segundo semestre de 2020 para apresentação à universidade Unifeb.

  O BetMajor é uma plataforma de notícias e apostas com ênfase no jogo CS:GO que permite ao usuário acompanhar atualizações e realizar apostas em seu time favorito.
  
  Ele possui um componente chamado conteúdo que, carrega às páginas sem atualizá-la, tal qual, é capaz de trazer a lista de estatísticas, as notícias, a página de administração, etc.

  A aplicação necessita de autenticação; guarda no banco de dados as publicações de notícias realizadas e as retorna de forma visual e agradável ao usuário final, além de, não permitir a realização de uma publicação caso o usuário não seja um administrador.

## Tecnologias
  Muitas ferramentas foram utilizadas para o seu desenvolvimento. Entre elas estão:

- NodeJs
  - Node Schedule
- VueJs
  - Vue MQ
  - Vue Router
  - Vue Toasted
  - Vue Editor
  - Vue Gravatar
  - Vue Bootstrap
  - Vuex
- PostgresSQL
- MongoDB
- Docker
- KnexJs
- Bcrypt
- Font Awesome
- Express
- CORS
- Axios
- Moment
- Passport
- JWT

## Ambiente de Desenvolvimento

  Para rodar essa aplicação, você precisará ter a ferramenta Docker previamente instalada em sua máquina.

**Clonando o repositório:**

```
$ git clone --recurse-submodules https://github.com/joaovictorneto/betmajor.git
```

To clone this repository (and its submodules) execute:  
`git clone --recurse-submodules https://github.com/sleeske/heroku-main.git`  

To start execute:  
`cd heroku-main && docker-compose up --build`

Additional setup might be required - consult **README.md** files in each submodule for details.

### Instalando:

**Back-End**

- Digite `npm install` na pasta `backend` para instalar todas as dependências;
- Digite `npm run dev:server` para rodar o servidor;

**Front-End** 

- Digite `npm install` na pasta `frontend` para instalar todas as dependências;
- Digite `npm start` para rodar o projeto;
