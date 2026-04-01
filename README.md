# 🚀 Projeto Back-end - Desenvolvimento Móvel

Este repositório contém a implementação do **Back-end** desenvolvido para a disciplina de **OPT-120 Desenvolvimento Móvel**. A API serve como o núcleo de processamento e persistência de dados, sendo consumida por uma aplicação front-end (Flutter).

## 📌 Sobre o Projeto

O objetivo principal deste serviço é fornecer uma interface de comunicação (API) para o gerenciamento de dados do aplicativo. Ele foi estruturado para garantir que a aplicação móvel tenha acesso rápido e seguro às informações armazenadas.

### 🛠️ Tecnologias Principais
* **Banco de Dados:** PostgreSQL (Persistência de dados relacional)
* **Finalidade:** Prover endpoints para consumo do Front-end em Flutter.
* **Arquitetura:** RESTful API.

---

## 🏗️ Arquitetura e Integração

O projeto segue o fluxo de comunicação padrão para aplicações móveis modernas:
1.  O **Frontend (Flutter)** realiza requisições HTTP (GET, POST, etc).
2.  Este **Back-end** processa as regras de negócio e validações.
3.  Os dados são persistidos ou recuperados do **PostgreSQL**.

## 🛠️ Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:

* [Node.js](https://nodejs.org/en/) (v16 ou superior)
* [NPM](https://www.npmjs.com/) (geralmente vem com o Node)
* [Docker](https://www.docker.com/) e **Docker Compose** (necessário para rodar o banco de dados de forma isolada)

## 🚀 Como rodar o projeto

### 1. Clonar o repositório

```bash
git clone [https://github.com/joao-pedro-inoe/opt120_backend.git](https://github.com/joao-pedro-inoe/opt120_backend.git)
cd opt120_backend
```
### 2. Configurar o Banco de Dados (Docker)

```bash
docker-compose up -d
```
### 3. Instalar as dependências

```bash
npm install
```
### 4. Executar a aplicação

```bash
npm start
```