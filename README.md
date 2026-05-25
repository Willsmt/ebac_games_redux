# 🎮 EBAC Games

Uma aplicação de loja virtual de games desenvolvida com React, TypeScript, Redux Toolkit e RTK Query.

O projeto simula um e-commerce simples de jogos, permitindo listar produtos, adicionar itens ao carrinho e calcular o valor total automaticamente utilizando gerenciamento de estado global com Redux.

---

# 🚀 Tecnologias Utilizadas

## Front-end

* React 18
* TypeScript
* Redux Toolkit
* RTK Query
* React Redux
* Styled Components

## Ferramentas

* ESLint
* Prettier
* Testing Library

---

# 📚 Conceitos Aplicados

Este projeto foi desenvolvido com foco em estudos e prática dos seguintes conceitos:

* Componentização no React
* Gerenciamento de estado global
* Redux Toolkit
* RTK Query
* Hooks do React
* Hooks do Redux
* Tipagem com TypeScript
* Styled Components
* Consumo de API
* Organização de pastas
* Boas práticas no React

---

# 📂 Estrutura do Projeto

```bash
src/
│
├── assets/
│
├── components/
│   ├── Header/
│   └── Produto/
│
├── containers/
│   └── Produtos/
│
├── services/
│   └── api.ts
│
├── store/
│   ├── reducers/
│   │   └── carrinho.ts
│   │
│   └── index.ts
│
├── styles/
│
├── App.tsx
└── main.tsx
```

---

# ⚙️ Funcionalidades

✅ Listagem de produtos
✅ Carrinho de compras global
✅ Soma automática do valor total
✅ Bloqueio de itens duplicados
✅ Consumo de API com RTK Query
✅ Estilização com Styled Components
✅ Tipagem completa com TypeScript

---

# 🛒 Fluxo da Aplicação

```text
Usuário
   ↓
Lista de Produtos
   ↓
Clique em "Adicionar ao carrinho"
   ↓
Redux Toolkit dispara action
   ↓
Reducer atualiza o estado global
   ↓
Header recalcula:
- quantidade de itens
- valor total
   ↓
React renderiza automaticamente
```

---

# 🔥 Redux Toolkit

O projeto utiliza Redux Toolkit para simplificar o gerenciamento de estado.

### Slice do Carrinho

Responsável por:

* armazenar os itens;
* adicionar produtos;
* impedir duplicação.

### Store Global

Centraliza:

* carrinho;
* cache da API;
* middleware.

---

# 🌐 RTK Query

O RTK Query foi utilizado para:

* fazer requisições HTTP;
* cache automático;
* controle de loading;
* integração direta com Redux.

---

# 🎨 Styled Components

A estilização foi feita utilizando Styled Components.

Benefícios:

* CSS isolado por componente;
* reutilização;
* manutenção facilitada;
* código mais organizado.

---

# 📦 Instalação do Projeto

## Clone o repositório

```bash
git clone URL_DO_REPOSITORIO
```

---

## Entre na pasta

```bash
cd loja
```

---

## Instale as dependências

```bash
npm install
```

---

# ▶️ Executando o Projeto

```bash
npm start
```

O projeto será iniciado em:

```bash
http://localhost:3000
```

---

# 🖥️ Fake API

O projeto utiliza uma API fake local.

Exemplo de endpoint:

```bash
http://localhost:4000/produtos
```

---

# 📌 Scripts Disponíveis

## Rodar o projeto

```bash
npm start
```

## Gerar build

```bash
npm run build
```

## Rodar testes

```bash
npm test
```

---

# 📖 Aprendizados

Durante o desenvolvimento deste projeto foram praticados conceitos importantes do ecossistema React moderno:

* React com TypeScript
* Redux Toolkit
* RTK Query
* Hooks personalizados
* Estado global
* Consumo de APIs
* Componentização
* Arquitetura Front-end

---

# 👨‍💻 Autor

Desenvolvido para estudos e prática de desenvolvimento Front-end moderno utilizando React + Redux Toolkit.

---
