Este é o repositório principal contendo docker-compose.yml para desenvolvimento local e os submódulos backend/frontend da aplicação.
<p align="center">
<!--   <img src="https://github.com/bprofiro/gofinances/blob/master/frontend/src/assets/logo.svg" /> -->
</p>

<p align="center">
<!--   <img src="https://github.com/bprofiro/assets/blob/master/In%C3%ADcio.png" /> -->
</p>

## Sobre o Projeto

  Esse projeto foi desenvolvido durante o segundo semestre de 2020 para apresentação à universidade Unifeb.

  O BetMajor é um aplicativo de notícias e apostas com ênfase no jogo CS:GO que permite ao usuário acompanhar atualizações e realizar apostas em seu time favorito.
  
  Ele possui duas páginas, o Dashboard, para listar as transações, as entradas saídas e total e a página de importação.

  A aplicação guarda no banco de dados as transações já feitas e as retorna de forma visual e agradável ao usuário final, além de não permitir a realização de uma transação de saída cujo o valor ultrapassa o valor em caixa.

## Tecnologias:
  Muitas ferramentas foram utilizadas para o seu desenvolvimento. Entre elas estão:

- Node
- Vue
  - Vue Icons
  - Vue Dropzone
  - Vue Dom
  - Vue Router
- Postgres
- MongoDB
- Docker
- KnexJs
- Date-fns
- Styled Components
- Express
- CORS
- Axios
- Multer
- ESlint
- Prettier

## Ambiente de Desenvolvimento

  Para rodar essa aplicação em sua máquina, você precisará do Docker instalado.

**Clonando o repositório:**

```
$ git clone https://github.com/bprofiro/gofinances/.git
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
