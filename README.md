![Logo](https://user-images.githubusercontent.com/56983783/123552822-59444780-d74e-11eb-88d1-31143874c1e0.png)

# Letmeask - perguntas e respostas

![GitHub watchers](https://img.shields.io/github/watchers/AlexBitar80/letmeask-nlw?style=social)  ![GitHub repo size](https://img.shields.io/github/repo-size/AlexBitar80/letmeask-nlw) ![GitHub Repo star](https://img.shields.io/github/stars/AlexBitar80/letmeask-nlw?style=social) ![GitHub Repo license](https://img.shields.io/github/license/AlexBitar80/letmeask-nlw) ![GitHub language count](https://img.shields.io/github/languages/count/AlexBitar80/letmeask-nlw) ![GitHub last commit](https://img.shields.io/github/last-commit/AlexBitar80/letmeask-nlw)

Projeto desenvolvido durante a 6° da Next Level Week evento da Rocketseat.

O letmeask é uma aplicação onde o usuário pode logar utilizando sua conta do Google, criar uma sala, e disponibilizar o código desta sala para outras pessoas.

Estas pessoas podem acessar a sala para fazer perguntas, visualizar e marcar como gostei perguntas feitas por outros participantes da sala, e o administrador da sala pode visualizar as perguntas em tempo real.

Não é necessário estar logado para visualizar as perguntas de outros participantes, mas caso queira fazer uma pergunta, será necessário.

## :rainbow: Tecnologias usadas nessa aplicação

-  [typescript](https://www.typescriptlang.org/)
-  [react.js](https://pt-br.reactjs.org/)
-  [create-react-app](https://create-react-app.dev/)
-  [react-router-dom](https://reactrouter.com/web/guides/quick-start)
-  [sass](https://sass-lang.com/)
-  [firebase](https://firebase.google.com/?hl=pt)

## :rocket: Tela inicial da aplicação

![Tela inicial1 da aplicação](https://user-images.githubusercontent.com/56983783/123552708-aecc2480-d74d-11eb-80cf-a4a8033a064c.png)

## :man_mechanic:  Como rodar a aplicação

Para rodar esta aplicação você vai precisar do [Node](https://nodejs.org/en/), do [Git](https://git-scm.com/) e do [yarn](https://yarnpkg.com/) ou npm, que por padrão já vem com o Node.

Clone o projeto

```bash
git clone https://github.com/AlexBitar80/letmeask-nlw letmeask
```

Vá até a pasta do projeto

```bash
cd letmeask
```

Instale as dependências

```bash
npm install | yarn
```

Rode o projeto

```bash
npm run start | yarn start
```

A aplicação está utilizando o firebase, para que ele funcione será necessário alguns passos.

- Vá até o [firebase](https://firebase.google.com/) (Será necessário ter uma conta do google para isso)
- No canto superior direito vá em ***Ir para o console***
- Clique em ***Adicionar novo projeto***
- Clique na engrenagem ao lado de ***Visão geral do projeto*** e vá em ***Configurações do projeto***
- Em geral role até a parte ***Configuração do SDK***
- selecione ***Configurações*** em vez de ***CDN***

No projeto crie um novo arquivo na raiz chamado ***.env.local*** Nesse formato,
substitua as informações com base nas que aparecem para você.


### :file_folder: Formato do arquivo
```bash
# FIREBASE

REACT_APP_API_KEY=""
REACT_APP_AUTH_DOMAIN=""
REACT_APP_DATABASE_URL=""
REACT_APP_PROJECT_ID=""
REACT_APP_STORAGE_BUCKET=""
REACT_APP_MESSAGING_SENDER_ID=""
REACT_APP_APP_ID=""
```

## :pushpin: Licença

Este projeto está sob a licença MIT [LICENSE](https://github.com/AlexBitar80/letmeask-nlw/blob/master/LICENSE) para mais detalhes.
