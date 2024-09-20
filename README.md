# Back-end
>O termo **"back-end"** se refere à parte do desenvolvimento de software que lida com a lógica, o armazenamento de dados e a comunicação entre o servidor e o cliente. É a "parte de trás" de um aplicativo ou site, que os usuários não veem diretamente, Principais componentes
>do back-end: Servidores: Computadores ou serviços que hospedam o aplicativo e processam solicitações Banco de Dados: Onde os dados são armazenados, como informações de usuários, produtos, etc. Exemplos incluem MySQL, PostgreSQL e MongoDB. APIs:

# node.js
>Node.js é um intrepretador de javascript que não depende do navegador. Ele permite que os desenvolvedores usem JavaScript para criar aplicações web escaláveis e rápidas. 

>Características do Node.js:
>Baseado em JavaScript: Permite que desenvolvedores utilizem a mesma linguagem tanto no front-end quanto no back-end, Utiliza o motor V8 do Google Chrome, que compila JavaScript diretamente para código de máquina, aumentando a performance, NPM  É amplamente utilizado em aplicações web, APIs, Node.js é uma excelente escolha para aplicações que exigem alta performance e que precisam lidar com muitas requisições simultâneas

# Como instalar o node?
* Abra uma guia no goole
* Pesquise por nodejs.e
* Logo você irá entrar na pagina oficial do node
* Hávera 2 versões
* A primeira versão é "lts", essa versão é a mais estavel
* A segunda versão é "current", essa versão é ultilizada para testes
* Em seguida entre no cmd 
* Coloque = node.e
* Ira aparecer a versão que foi imposta no começo do download


# Como ultilizar comandos
* Inicialize o projeto com npm:
npm init -y

### Instale o Express
npm install express
  
### Configure o servidor: 
* const express = require('express'); 
* const app = express(); 
* app.use(express.json()) 
* app.get('/', (req, res) => { 
* res.json({ msg:”Olá” }); 
 }); 
*app.listen(3000); 

### Execute o servidor: 
* node app.js 
* Acesse o navegador ou Postman e digite: 

![12](https://github.com/user-attachments/assets/4d80dc08-b6a4-4596-a962-4315880a1abc)


# API
* Cada API tem uma documentação que explica como usá-la. Isso inclui:
Endpoints: URLs que você pode chamar.

* Fazer uma Requisição
Você pode usar várias ferramentas e bibliotecas para fazer requisições a APIs. 

* Após fazer a requisição, você receberá uma resposta. Essa resposta pode incluir dados que você pode usar em sua aplicação. Normalmente, ela está no formato JSON.

 * Autenticação (se necessário)
Muitas APIs exigem algum tipo de autenticação (por exemplo, tokens de API). Isso geralmente envolve:
Adicionar um cabeçalho de autorização:

 * Manipulação de Erros
É importante tratar erros que podem ocorrer durante a requisição. Isso pode incluir falhas de rede, respostas não bem-sucedidas, etc.

* Praticar
Experimente diferentes APIs públicas (como a API do GitHub, OpenWeatherMap, etc.) para se familiarizar com o processo.


# O que é mYSQL
MySQL é um sistema de gerenciamento de banco de dados relacional (RDBMS) que utiliza a linguagem SQL (Structured Query Language) para gerenciar e manipular dados. É um dos bancos de dados mais populares do mundo, conhecido por sua eficiência, confiabilidade e facilidade de uso.

## Principais características do MySQL:

* Relacional: Organiza os dados em tabelas que podem se relacionar entre si, permitindo consultas complexas.

* Open Source: É um software de código aberto, o que significa que é gratuito e a comunidade pode contribuir para seu desenvolvimento.

* Desempenho: Otimizado para consultas rápidas, pode lidar com grandes volumes de dados de forma eficiente.







