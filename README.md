# Blog com Angular

Projeto de blog desenvolvido com Angular 10 no front-end e JSON Server como API mockada no back-end. O nome do repositório menciona Java, mas a versão armazenada aqui usa Node.js para servir os dados de `banco.json`.

## Estrutura

```text
backend/   # JSON Server
frontend/  # Angular 10
```

## Pré-requisitos

- Node.js em versão compatível com Angular CLI 10.
- npm.

## Executar o back-end

```bash
cd backend
npm install
npm start
```

A API mockada fica em `http://localhost:3000`.

## Executar o front-end

Em outro terminal:

```bash
cd frontend
npm install
npm start
```

O Angular serve a aplicação, normalmente, em `http://localhost:4200`.

## Stack

- Angular 10 e TypeScript
- Angular Router
- Bootstrap 4
- Font Awesome
- JSON Server

O projeto foi reorganizado para deixar `backend/` e `frontend/` diretamente na raiz.
