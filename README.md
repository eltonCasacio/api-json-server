# json-server

**json-server é ideal para quem só precisa receber dados em formato JSON para testes de requisção GET, POST, PUT e DELETE.**

**RODAR COM DOCKER**
    1 - Entre na pasta api-json-server
    2 - Execute o comando: `docker-compose up`
    3 - [Abra o browser e acesse: http://0.0.0.0:3001/products](http://0.0.0.0:3001/products)

    comando para parar o processo `docker-compose down`

**Observação:** 
    Se der algum erro na hora de parar o processo, tente executar o comando: 
    `sudo aa-remove-unknown`



**COM O NODE INSTALADO**
    1 - Entre na pasta api-json-server
    2 - `npm install`
    3 - `npm start`