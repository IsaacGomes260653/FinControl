# FinControl MVP 💰

Um aplicativo web de controle financeiro responsivo e completo, construído no formato Single Page Application (SPA) para simular uma experiência nativa de smartphone diretamente no navegador.

## 🚀 Como Executar

Este projeto foi desenhado com uma arquitetura **Zero Config**, permitindo execução imediata sem a necessidade de um ambiente de desenvolvimento complexo.

1. Faça o clone deste repositório ou baixe o arquivo `.zip`.
2. Dê um duplo clique no arquivo `index.html` para abri-lo no seu navegador.
3. Pronto! O app já está rodando perfeitamente.

> **Teste a versão online:** (https://isaacgomes260653.github.io/FinControl/)

## 🔐 Credenciais para Teste

Para facilitar a visualização e avaliação do projeto, você pode entrar no aplicativo utilizando a senha padrão de testes:

- **Senha de acesso:** `123456`

*(Nota: Como o app utiliza o armazenamento local do seu navegador, você também pode testar o fluxo criando uma nova conta, se desejar!)*

## ✨ Funcionalidades

- **Autenticação Simulada:** Fluxo visual completo de Login, Criação de Conta e Recuperação de Senha.
- **Dashboard Financeiro:** Resumo de saldo disponível com controle automático de receitas e despesas.
- **Controle de Orçamento:** Acompanhamento dinâmico de gastos por categoria (Alimentação, Transporte, Saúde, etc.) através de gráficos em anel (*Ring Charts*).
- **Gestão de Transações:** Adição de novas movimentações e extrato detalhado diário.
- **Persistência de Dados:** O estado do usuário, orçamentos e transações são salvos localmente utilizando a API de `localStorage` do navegador. Os dados não se perdem ao atualizar a página.

## 🛠️ Tecnologias Utilizadas

- **[React 18](https://reactjs.org/):** Importado via CDN para componentização e renderização reativa das telas e estados (`useState`, `useEffect`, `useCallback`).
- **[Babel Standalone](https://babeljs.io/docs/en/babel-standalone):** Para compilação do código JSX e ES6+ em tempo real no navegador.
- **HTML5 & CSS3:** Estilização componentizada em blocos in-line, sem a necessidade de frameworks adicionais de CSS.
- **Ícones SVG Nativos:** Renderização otimizada e construída matematicamente via código (`<svg>`), dispensando o uso de bibliotecas pesadas de ícones.

## 📂 Arquitetura

O projeto utiliza um modelo prático para MVPs (*Minimum Viable Products*) em um formato *All-in-One File*. Diferentes telas (Dashboard, Login, Criar Conta) e pequenos componentes UI (Status Bar nativa, Bottom Nav, Gráficos) são separados por funções lógicas puras dentro do mesmo escopo para garantir rápida implantação e fluidez.

---
Desenvolvido por **Isaac Gomes de Moraes**

---

# FinControl MVP 💰 (English)

A responsive, full-featured personal finance web app built as a Single Page Application (SPA) that simulates a native smartphone experience directly in the browser.

## 🚀 Running it

Built with a **Zero Config** architecture — no build tools or dev environment needed.

1. Clone this repository or download the `.zip`.
2. Double-click `index.html` to open it in your browser.
3. Done! The app is already running.

> **Live demo:** https://isaacgomes260653.github.io/FinControl/

## 🔐 Test credentials

- **Password:** `123456`

*(The app uses browser `localStorage`, so you can also test the full flow by creating a new account.)*

## ✨ Features

- **Simulated authentication:** full Login, Sign Up, and Password Recovery flow.
- **Financial dashboard:** available balance summary with automatic income/expense tracking.
- **Budget control:** dynamic spending tracked by category (Food, Transport, Health, etc.) via ring charts.
- **Transaction management:** add new transactions and view a detailed daily statement.
- **Data persistence:** user state, budgets, and transactions are saved locally via the browser's `localStorage` API — nothing is lost on refresh.

## 🛠️ Tech stack

- **[React 18](https://reactjs.org/)** via CDN for componentization and reactive rendering (`useState`, `useEffect`, `useCallback`).
- **[Babel Standalone](https://babeljs.io/docs/en/babel-standalone)** to compile JSX/ES6+ in the browser at runtime.
- **HTML5 & CSS3:** inline component styling, no extra CSS framework needed.
- **Native SVG icons:** lightweight, code-built icons instead of a heavy icon library.

## 📂 Architecture

A practical **All-in-One File** MVP structure: different screens (Dashboard, Login, Sign Up) and small UI components (native status bar, bottom nav, charts) are split into pure functions within the same scope for fast, fluid delivery.

---
Built by **Isaac Gomes de Moraes**
