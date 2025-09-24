
# ⚙️ Mini Flow Automator (tipo mini-Zapier)

> **Projeto de portfólio** para demonstrar habilidades em **Node.js, Express, SQLite, automação e integração de APIs**.  
> Um sistema que permite criar **fluxos de automação personalizados**, combinando **triggers** (gatilhos) e **steps** (ações).

---

## 🚀 O que é este projeto?

O **Mini Flow Automator** é uma aplicação web que permite montar fluxos automáticos sem precisar programar.  
Com ele, é possível:

- Criar **gatilhos** (triggers) para iniciar o fluxo:  
  - **Webhook** → recebe dados externos via POST  
  - **Intervalo** → executa de X em X segundos  

- Configurar **etapas** (steps) do fluxo:  
  - 🔗 **http_request** → consome APIs externas  
  - 🧠 **transform** → processa dados com snippets JavaScript  
  - ⏱ **delay** → pausa a execução  
  - 📤 **webhook** → envia resultados para outro sistema  
  - 📝 **log** → registra informações no banco de dados  

---

## ✨ Principais destaques
- **Interface Web simples e responsiva** (Nunjucks + CSS customizado)  
- **Banco local SQLite** para armazenar flows e logs  
- **Motor de execução** com logs detalhados  
- **Templating `{{ }}`** para usar variáveis dinâmicas em qualquer campo  
- **Exemplo pronto** já incluso (busca dados de uma API, processa e envia para um webhook)  

---

## 📸 Demonstração

Aqui está um exemplo de como adicionar um **GIF ou print de tela** da aplicação em funcionamento:  

![Demonstração do Mini Flow Automator](./docs/demo.gif)  

> 📌 Coloque sua imagem ou GIF dentro de uma pasta `docs/` na raiz do repositório, e troque o nome do arquivo no link acima.  

---

## 📂 Estrutura do projeto
```
mini-flow-automator/
├── README.md
├── DOCUMENTACAO_PORTFOLIO.md   → Documentação técnica completa
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

---

## 🚀 Como rodar localmente
```bash
# 1. Clone o repositório
git clone https://github.com/SEU-USUARIO/mini-automatizador-de-fluxo.git

# 2. Entre na pasta do servidor
cd mini-automatizador-de-fluxo/server

# 3. Instale as dependências
npm install

# 4. Inicie o projeto
npm start
```

Abra no navegador:  
👉 `http://localhost:3000`

---

## 📖 Documentação completa
Para detalhes sobre **dependências, .gitignore, estrutura e passo a passo para publicar no GitHub**, acesse:  

➡️ [DOCUMENTACAO_PORTFOLIO.md](./DOCUMENTACAO_PORTFOLIO.md)

---

## 💼 Por que esse projeto é ideal para portfólio?
- Mostra conhecimento em **backend, frontend e banco de dados**.  
- Demonstra **integração com APIs** e automação de fluxos.  
- Código limpo, documentado e com README profissional.  
- Fácil de testar e **expandir** (dá pra criar novos steps ou triggers).  

---

## 📝 Licença
MIT – livre para usar, modificar e publicar.  
