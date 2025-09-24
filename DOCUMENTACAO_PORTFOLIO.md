
# 📂 Mini Flow Automator – Documentação de Portfólio

Este documento complementa o README e explica em detalhes a estrutura do projeto, as dependências, o .gitignore e como publicar no GitHub.

## ⚙️ Sobre o Projeto
Sistema estilo **mini-Zapier** que permite criar automações com triggers (webhook/interval) e steps (http_request, transform, delay, webhook, log).

## 📦 Dependências
- express
- nunjucks
- better-sqlite3
- uuid
- morgan

Instale com:
```bash
npm install
```

## 📂 Estrutura
```
mini-flow-automator/
├── README.md
├── DOCUMENTACAO_PORTFOLIO.md
└── server/
    ├── package.json
    ├── .gitignore
    ├── index.js
    ├── db.js
    ├── flows.js
    ├── utils.js
    ├── views/
    ├── public/
    └── data.db
```

## 📑 .gitignore
Ignora `node_modules/`, `.db`, `.env`, logs, configs locais de IDEs, builds e temporários.

## 🚀 Rodando localmente
```bash
cd server
npm install
npm start
```

Acesse: `http://localhost:3000`

## 📤 Publicar no GitHub
1. Crie o repositório no GitHub (público, sem README/.gitignore).  
2. No terminal:
```bash
git init
git add .
git commit -m "Primeira versão do Mini Flow Automator"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/mini-automatizador-de-fluxo.git
git push -u origin main
```
