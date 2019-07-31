![Logo](https://cdn4.iconfinder.com/data/icons/logos-3/600/React.js_logo-512.png)

# MyMoney - Back-end

## Instalação e configuração

1. Recomendado a utilização do [ASDF](https://asdf-vm.com/#/core-manage-asdf-vm) para criação do ambiente de desenvolvimento
2. Após ambiente com [NodeJs](https://nodejs.org/en/download/) configurado, execute a instalação das dependências com `npm i`
3. É necessário ter o [mongoDB](https://www.mongodb.com/) instalado e configurado
4. Em `src/server.js` configure a porta em que a aplicação irá rodar
5. Em `src/database.js` configure os dados de acesso ao banco de dados
6. Após tudo configurado, execute o comando: `npm run production`
7. Se quiser monitorar a aplicação em tempo real, pode executar o seguinte comando: `node_modules/.bin/pm2 monit`