# Hair Day ✂️

Aplicação Web de agendamentos para corte de cabelo.

## 💻 Sobre o projeto

Este projeto foi desenvolvido durante a trilha **Fullstack da Rocketseat**. O **Hair Day** consiste em um desafio de desenvolvimento focado na prática de conceitos essenciais de programação web e construção de interfaces.

O objetivo principal foi criar uma aplicação funcional para gerenciar horários de corte de cabelo, exercitando:
*   **Estados e Imutabilidade**: Gerenciamento do estado da aplicação de forma previsível.
*   **Listas e Propriedades**: Renderização dinâmica de dados.
*   **Componentização**: Criação de blocos de código reutilizáveis.
*   **Requisições HTTP**: Prática de métodos `GET` e `POST` consumindo uma API JSON.

## ⚙️ Funcionalidades

*   📅 **Agendar Horário**: Permite criar novos agendamentos preenchendo nome e escolhendo data/hora.
*   👀 **Visualizar Agenda**: Exibe a lista de clientes agendados e seus respectivos horários.
*   ❌ **Remover Agendamento**: Funcionalidade para cancelar/deletar um agendamento da lista.
*   📝 **Inputs Variados**: Utilização de diferentes tipos de campos de entrada para garantir uma boa experiência de usuário.

## 🛠 Tecnologias e Bibliotecas (NPM)

O projeto utiliza um ambiente moderno de desenvolvimento JavaScript configurado manualmente:

*   **Webpack**: Para empacotamento de módulos e servidor de desenvolvimento (`webpack-dev-server`).
*   **Babel**: Para garantir compatibilidade do código JavaScript moderno com diversos navegadores.
*   **Day.js**: Biblioteca leve para manipulação e formatação de datas e horários.
*   **JSON Server**: Utilizado para simular uma API REST completa, permitindo persistência de dados em um arquivo JSON local.
*   **Loaders (CSS/Style/Babel)**: Para processamento de arquivos de estilo e scripts.

## 🚀 Como executar o projeto

### Pré-requisitos

Certifique-se de ter o **Node.js** instalado em sua máquina.

### Instalação

1. Abra o terminal na pasta do projeto e instale as dependências:

```bash
npm install
```

### Executando a API (Backend)

O projeto utiliza o `json-server` para simular o backend. É necessário rodá-lo para que os dados sejam salvos e carregados.

```bash
npm run server
```
> O servidor iniciará na porta **3333** e observará o arquivo `server.json`.

### Executando a Aplicação (Frontend)

Em um **segundo terminal**, inicie o servidor de desenvolvimento do Webpack:

```bash
npm run dev
```
> A aplicação estará disponível no navegador (geralmente em `http://localhost:8080` ou porta similar indicada no terminal).

## 📡 Estrutura da API

A comunicação com o backend simulado é feita via JSON:
*   **GET**: Recupera a lista de agendamentos salvos.
*   **POST**: Envia os dados de um novo agendamento para serem salvos no `server.json`.

## 📝 Autor

Desenvolvido por **Leonardo Bruchez**.
