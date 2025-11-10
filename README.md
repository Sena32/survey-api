<div align="center">

# 🧾 **Survey API**

**RESTful API built with Node.js and TypeScript to calculate NPS (Net Promoter Score).**  
Developed during the **Next Level Week (NLW)** event by [Rocketseat](https://rocketseat.com.br/).

[![Status](https://img.shields.io/badge/status-active-brightgreen?style=for-the-badge)]()
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)]()
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)]()
[![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)]()
[![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)]()
[![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)]()

</div>

---

### 🧠 **Sobre o projeto**

A **Survey API** é uma aplicação backend desenvolvida em **Node.js com TypeScript** para realizar o cálculo de **NPS (Net Promoter Score)**.  
Ela permite o cadastro de usuários e pesquisas, envio de e-mails com formulários e cálculo automático do índice de satisfação.

---

### ⚙️ **Funcionalidades**

- [x] Listagem de pesquisas  
- [x] Criação de pesquisas  
- [x] Criação de usuários  
- [x] Envio de e-mails com link da pesquisa  
- [x] Cálculo do NPS (Net Promoter Score)

---

### 🧱 **Stack utilizada**

| Tipo | Tecnologias |
|------|--------------|
| **Linguagem** | Node.js + TypeScript |
| **Framework** | Express |
| **Banco de Dados** | SQLite |
| **Testes** | Jest |
| **Outros** | Nodemailer, TypeORM |

---

🛣️ Endpoints principais

Base URL: http://localhost:3333

| Método | Rota                                 | Descrição                               |
| ------ | ------------------------------------ | --------------------------------------- |
| `POST` | `/users`                             | Cria um novo usuário                    |
| `POST` | `/surveys`                           | Cria uma nova pesquisa                  |
| `GET`  | `/surveys`                           | Lista todas as pesquisas                |
| `POST` | `/sendMail`                          | Envia e-mail de pesquisa para o usuário |
| `GET`  | `/answers/:value?u={survey_user_id}` | Registra resposta da pesquisa           |
| `GET`  | `/nps/:survey_id`                    | Calcula o NPS da pesquisa               |


### 🧪 **Como executar localmente**

```bash
# Clone o repositório
git clone https://github.com/Sena32/survey-api.git

# Entre na pasta
cd survey-api

# Instale as dependências
npm install
# ou
yarn

# Execute a aplicação
npm run dev
# ou
yarn dev
```
<br />
<div align="center">
  <small>Developed by Ailton de Sena Pinheiro - 09/2023</small>

  [![GitHub Badge](https://img.shields.io/badge/Ailton_Sena-000?style=for-the-badge&logo=github&logoColor=white&link=https://www.linkedin.com/in/ailtonsenap)](https://github.com/Sena32/)
    [![Linkedin Badge](https://img.shields.io/badge/Ailton_Sena-000?style=for-the-badge&logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/ailtonsenap)](https://www.linkedin.com/in/ailtonsenap/) 
</div>
