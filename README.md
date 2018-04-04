# ifatec-mobile
Versão mobile do site da fatec

## Descrição

O ifatec-mobile a versão mobile do site ifatec.com.br, feito utilizando o cordova.

## Instalação

Para realizar a instalação será necessário:
 - Ter o nodeJs instalado.
 - Instalar o cordova atraves do  `npm install -g cordova `.
 - Clonar o projeto.
 - Acessar a pasta do projeto e baixar as dependencias com ` npm install `

## Adicionar plataforma

Atualmente o projeto esta apenas com as plataformas browser e android, caso deseje adicionar outra use:
 - `cordova platform add browser`  - plataforma web
 - `cordova platform add ios`      - plataforma ios
 - `cordova platform add android`  - plataforma android 

## Executar o projeto

Para executar o projeto use:
 - `cordova run browser` - para rodar na plataforma browser
 - `cordova run android`  - para rodar na plataforma android no emulador
 - `cordova run android --device`  -  para rodar na plataforma android no device

## Buildar o projeto

### Android

 - use `cordova build android`
