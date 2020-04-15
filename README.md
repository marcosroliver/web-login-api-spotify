# Fluxo de Autenticação API Spotify

Este projeto possui um exemplo do fluxo do código de autorização para acesso as informações do Spotify.

## Requisitos

* NodeJs
* NPM
* Windows/MacOS
* Rodar a aplicação na porta 8888

## Instalação 

Esta aplicação deve rodar no Node.js e utilizar o gerenciador de pacotes NPM.  [Aqui](http://www.nodejs.org/download/) você consegue encontrar o pacote de instalação e [aqui](https://gist.github.com/isaacs/579814) um exmplo de como intala-los.

Depois de instalado clone o repositório e instale as depências rodando o comando <b> npm install</b> no seu CMD/Ternminal.
    
Este conector está configurado para devolver os dados para a <b>porta http://localhost:3000/</b>

Caso sua aplicação esteja em outra porta configure o redirect no aquivo server.js conforme imagem abaixo:

incluir imagem


## Rodando a aplicação
Abra o CMD/Terminal navege até a pasta do projeto, e digite o comando <b>node server.js</b>

Agora basta navegar para a porta https://localhost:8888/login

Se preferir você pode criar um botão em sua aplicação que acesse esse endereço.

