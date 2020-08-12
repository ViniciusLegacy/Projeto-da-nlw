 # Proffy | Sua plataforma de estudos online
 
 Esse projeto é basicamente uma plataforma de estudos para conectar alunos e professores. Ele foi desenvolvido usando as seguintes tecnologias:

* HTML5
* CSS
* Javascript
* Bando de dados SQLite
* Node.js - versão(12.18.3)
* Git Bash

## Instalação



 Foi utilizado o terminal do Git bash dentro do vscode para instalar as dependências e rodar a aplicação em um servidor local. A configuração do servidor foi feita no arquivo server.js.

 ## Comandos
 
 - `npm init -y` // esse comando foi utilizado para criar o arquivo package.json dentro da aplicação.
 - `npm install express` // esse comando foi utilizado para fazer a instalação das dependências do projeto.
 - `npm install nodemon -D` // esse comando foi utilizado para instalar o nodemon que vai servir para monitorar o node e quando algum    arquivo for modificado ele vai reiniciar o servidor automaticamente. Para utilizar o nodemon foi feito a seguinte configuração 
 "dev": "nodemon src/server.js" - dentro do arquivo package.json.
 - `npm run dev` // esse comando foi utilizado para rodar o nodemon dentro da aplicação.
 - `npm install nunjucks` // esse comando foi utilizado para instalar a ferramenta nunjucks.