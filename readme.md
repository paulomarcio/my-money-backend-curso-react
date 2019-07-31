![Logo](http://pluspng.com/img-png/nodejs-logo-png--375.png)

# MyMoney - Back-end

## Instalação e configuração

1. Recomendado a utilização do [ASDF](https://asdf-vm.com/#/core-manage-asdf-vm) para criação do ambiente de desenvolvimento
2. Após ambiente com [NodeJs](https://nodejs.org/en/download/) configurado, execute a instalação das dependências com `npm i`
3. É necessário ter o [mongoDB](https://www.mongodb.com/) instalado e configurado
4. Faça uma cópia do arquivo `.env.example` como `.env`
5. No arquivo `.env` altere os valores `APP_PORT`, para a porta desejada, e `DB_URI` com os dados de acesso ao banco de dados
6. Após tudo configurado, execute o comando: `npm run production`
7. Se quiser monitorar a aplicação em tempo real, pode executar o seguinte comando: `node_modules/.bin/pm2 monit`