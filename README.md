# 🛒 Lista de Compras

## 📌 Sobre o projeto

O **Lista de Compras** é um aplicativo mobile desenvolvido com React Native, Expo e TypeScript, com o objetivo de facilitar a organização de produtos que precisam ser comprados. O aplicativo permite adicionar produtos, informar suas quantidades, visualizar os itens cadastrados e remover produtos da lista de maneira simples e intuitiva.

O projeto foi desenvolvido com foco na prática de conceitos fundamentais do desenvolvimento de aplicativos, como componentes, gerenciamento de estados, propriedades (props), tipagem com TypeScript e organização do código.

## 🎯 Objetivos

* Desenvolver um aplicativo de lista de compras funcional.
* Praticar a criação e reutilização de componentes.
* Utilizar estados para atualizar a lista dinamicamente.
* Aplicar interfaces e tipagem com TypeScript.
* Implementar funcionalidades de cadastro e remoção de produtos.
* Organizar o projeto em arquivos e componentes reutilizáveis.

## ⚙️ Tecnologias utilizadas

* **React Native:** desenvolvimento da interface do aplicativo.
* **Expo:** configuração, execução e testes do projeto.
* **TypeScript:** tipagem e organização do código.
* **JavaScript:** lógica e funcionamento das funcionalidades.
* **Node.js e npm:** gerenciamento de dependências e execução dos comandos.

## ✨ Funcionalidades

* **Adicionar produtos:** cadastrar produtos informando nome e quantidade.
* **Listar produtos:** visualizar todos os itens adicionados.
* **Remover produtos:** excluir itens da lista por meio de um botão.
* **Validar campos:** impedir o cadastro quando o nome do produto estiver vazio.
* **Quantidade padrão:** utilizar a quantidade 1 quando o campo de quantidade não for preenchido.
* **Lista vazia:** exibir uma mensagem quando não houver produtos cadastrados.
* **Contador de itens:** mostrar a quantidade de produtos registrados na lista.

## 📂 Estrutura do projeto

```text
lista-de-compras/
├── components/
│   ├── Cabecalho.tsx
│   ├── FormularioItem.tsx
│   ├── ItemCompra.tsx
│   └── ListaCompras.tsx
├── App.tsx
├── index.tsx
├── types.ts
├── app.json
├── babel.config.js
├── tsconfig.json
└── package.json
```

## 🚀 Como executar o projeto

### Pré-requisitos

* Node.js instalado.
* npm instalado.
* Visual Studio Code ou outro editor de código.
* Expo Go no celular ou um emulador compatível, caso queira testar o aplicativo em um dispositivo móvel.

### Instalação

**1. Clone o repositório:**

```bash
git clone URL_DO_SEU_REPOSITORIO
```

**2. Entre na pasta do projeto:**

```bash
cd lista-de-compras
```

**3. Instale as dependências:**

```bash
npm install
```

**4. Inicie o Expo:**

```bash
npm start
```

Após iniciar o projeto, utilize o QR Code exibido no terminal para abrir o aplicativo pelo Expo Go, ou siga as opções apresentadas para executar em uma plataforma compatível.

## 🧪 Testes realizados

O projeto prevê testes das principais funcionalidades, incluindo:

* Adicionar um produto com nome e quantidade.
* Verificar a validação de um nome vazio.
* Adicionar um produto sem informar a quantidade.
* Remover um produto da lista.
* Verificar o comportamento da lista quando todos os itens forem removidos.
* Conferir a atualização do contador de itens.
* Verificar erros de tipagem com o comando `npm run typecheck`.

## 📚 Conceitos praticados

Durante o desenvolvimento, são aplicados conceitos importantes, como `useState` para gerenciamento de estados, props para comunicação entre componentes, `FlatList` para renderização eficiente de listas, `TextInput` para entrada de dados, `TouchableOpacity` para interação com botões e interfaces do TypeScript para definir a estrutura dos dados.

## 👩‍💻 Aprendizado

Este projeto contribui para o aprendizado prático do desenvolvimento mobile, permitindo compreender como estruturar uma aplicação, dividir funcionalidades em componentes e manipular informações dinamicamente com React Native e TypeScript.

---

**Projeto educacional — Desenvolvimento de Sistemas.**
