# Projeto Be The Hero

## **Finalidade**
Criar uma aplicação completa (backend, web e mobile) com o objetivo de ser uma aplicação para
auxílio e caridade para instituições, onde um doador é capaz de encontrar uma ONG e dar suporte
a um caso específico de necessidade da ONG.

## **Backend**
No backend foi usado NodeJS, e bibliotecas como express (criação do servidor e rotas), cors (configuração do servidor), axios (uso com api), knex e sqlite3 (conexão com BD).
Além destes também foi usado o nodemon como dependência de desenvolvimento.

O Banco de Dados utilizado foi o BD relacional Sqlite3 através do Knex, podendo facilmente ser escalado para um banco mais complexo como o postgreSQL. Ele foi usado localmente, utilizado em conjunto com migrations da biblioteca knex.

As validações para acesso fora feitas utilizando o celebrate, um middleware para a biblioteca express.

Os testes foram realizados utilizando o Jest.

![backend](https://raw.githubusercontent.com/williamguilhermesouza/omnistack11/master/screenshots/back_routes.png)

## **Web**
No frontend web a aplicação foi desenvolvida utilizando o ReactJS, aliado ao CSS3 e HTML da página juntamente com todas as dependências usadas através do "create react-app".

Também foi usado o axios para contato com o backend através de uma API. 

![web](https://raw.githubusercontent.com/williamguilhermesouza/omnistack11/master/screenshots/front_index.png)

![web1](https://raw.githubusercontent.com/williamguilhermesouza/omnistack11/master/screenshots/front_incNew.png)

![web2](https://raw.githubusercontent.com/williamguilhermesouza/omnistack11/master/screenshots/front_profile.png)

![web3](https://raw.githubusercontent.com/williamguilhermesouza/omnistack11/master/screenshots/front_register.png)

## **Mobile**
A aplicação mobile foi criada utilizando React Native, através do expo, uma ferramente que abstrai a instalação do android SDK, tornando mais simples e rápida a entrega de uma aplicação mobile. 

No desenvolvimento dessa parte da aplicação foram usadas bibliotecas nativas para o react native e para o próprio expo, como também a funcionalidade Intl, capaz de formatar campos dependendo das unidades utilizadas.

Além disso, foi implementado um sistema simples de paginação, e funções que levam a aplicação a aplicações externas para contato por E-mail e por WhatsApp.

Também foi utilizado o axios para comunicação com API.


<img src="https://raw.githubusercontent.com/williamguilhermesouza/omnistack11/master/screenshots/mobile_incidents.png" alt="mobile1" width="250" height="400"> | 
<img src="https://raw.githubusercontent.com/williamguilhermesouza/omnistack11/master/screenshots/mobile_detail.png" alt="mobile2" width="250" height="400"> | 
<img src="https://raw.githubusercontent.com/williamguilhermesouza/omnistack11/master/screenshots/mobile_email.png" alt="mobile3" width="250" height="400"> | 


***

As imagens da aplicação final, encontram-se na pasta "screenshots".

### Autor: William Souza
