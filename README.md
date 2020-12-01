Este é o repositório principal contendo docker-compose.yml para desenvolvimento local e os submódulos backend/frontend da aplicação.
<p align="center">
   <img src="https://github.com/joaovictorneto/betmajor-frontend/blob/main/src/assets/logo_betmajor_preta.png" />
</p>

## Sobre o Projeto

  Esse projeto foi desenvolvido durante o segundo semestre de 2020 para apresentação à universidade Unifeb.

  O BetMajor é uma plataforma de notícias e apostas com ênfase no jogo CS:GO que permite ao usuário realizar apostas e acompanhar atualizações de noticias de seu time favorito.
  
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
- Heroku

## Ambiente de Desenvolvimento

  Para rodar essa aplicação, você precisará ter a ferramenta Docker previamente instalada em sua máquina.

**Clonando o repositório:**

```
$ git clone --recurse-submodules https://github.com/joaovictorneto/betmajor.git
```

**Executando:**

```
$ cd betmajor && docker-compose up --build
```

É necessário ver detalhes de configuração adicional nos submódulos. Consulte os arquivos **README.md** de cada repositório.
