# Product List Firebase

Aplicacao React para cadastro e controle simples de produtos por usuario, usando Firebase Authentication e Firebase Realtime Database.

## Funcionalidades

- Cadastro e login com email e senha.
- Login com Google.
- Listagem de produtos por usuario autenticado.
- Cadastro de produto com descricao e quantidade.
- Remocao de produtos.
- Pagina de perfil e navegacao com React Router.

## Tecnologias

- React 18
- React Router DOM
- Firebase Authentication
- Firebase Realtime Database
- Material UI
- Bootstrap
- Create React App

## Requisitos

- Node.js 18 ou superior
- NPM
- Projeto Firebase configurado com Authentication e Realtime Database

## Configuracao

Configure as credenciais do Firebase no arquivo usado pela aplicacao em `src/components/firebaseConfig.js`. Use os dados do seu projeto no Firebase Console e mantenha chaves sensiveis fora do historico quando estiver trabalhando com ambientes reais.

## Rodando localmente

```bash
git clone https://github.com/gb-araujo/product-list-firebase.git
cd product-list-firebase
npm install
npm start
```

A aplicacao sera aberta em `http://localhost:3000`.

## Scripts disponiveis

| Comando | Descricao |
| --- | --- |
| `npm start` | Inicia o servidor de desenvolvimento |
| `npm test` | Executa os testes do Create React App |
| `npm run build` | Gera a versao de producao em `build/` |

## Estrutura principal

```text
src/
  components/
    login.js              # Autenticacao com email/senha e Google
    ListaDeProdutos.js    # CRUD de produtos por usuario
    daoTask.js            # Acesso ao Realtime Database
    Perfil.js             # Pagina de perfil
  App.js                  # Rotas da aplicacao
```

## Proximos passos sugeridos

- Mover configuracoes de ambiente para `.env`.
- Adicionar validacoes de formulario.
- Criar feedback visual para carregamento e erros.
- Adicionar testes para fluxo de autenticacao e produtos.
