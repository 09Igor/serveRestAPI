# 🚀 Bootcamp #01 Qualiters Club  
Teste de API REST - Do Manual ao CI/CD

---

## 📌 Sobre o Projeto
Este repositório foi criado para o **Bootcamp de Testes de API REST**. Ele inclui a automação de testes com **Newman** e integração com **CI/CD**, garantindo a validação contínua das APIs.

---

## 🛠 Tecnologias Utilizadas
- **Postman** (Versão Web)
- **Node.js** v22.13
- **Newman** v6.2.1
- **Newman HTML Reporter** (htmlextra)
- **GitHub Actions** (para execução automatizada)

---

## 📄 Documentação da API
A API utilizada nos testes pode ser acessada via **Swagger**:
🔗 [Consulte a Documentação](https://serverest.dev/)

---

## 🔧 Configuração do Ambiente
Siga os passos abaixo para configurar e executar os testes:

### 1️⃣ Instalar o Node.js
Baixe e instale a versão mais recente do **Node.js**:  
🔗 [Download Node.js](https://nodejs.org/pt)

### 2️⃣ Instalar o Newman
Instale o **Newman** globalmente para rodar os testes do Postman via linha de comando:
```sh
npm install -g newman
```
🔗 [Newman - npm](https://www.npmjs.com/package/newman)

### 3️⃣ Instalar o Reporter HTML (Opcional)
Caso queira gerar relatórios detalhados em HTML:
```sh
npm install -g newman-reporter-htmlextra
```
🔗 [Newman HTML Reporter](https://www.npmjs.com/package/newman-reporter-htmlextra)

---

## ▶️ Como Rodar os Testes
### Executar testes via Newman (linha de comando)
```sh
newman run serverest.postman_collection.json -e ServeRest.postman_environment.json -r cli,htmlextra
```

### Gerar relatório HTML dos testes
```sh
newman run serverest.postman_collection.json -e ServeRest.postman_environment.json -r htmlextra
```
O relatório será salvo no diretório **newman**.

## 📬 Entre em Contato
📧 E-mail: pondeigor09@gmail.com  
📌 Repositório: [GitHub - 09Igor/serveRestAPI](https://github.com/09Igor/serveRestAPI)
