# json-server




### RODAR COM DOCKER ###  

   1 - Entre na pasta api-json-server
   
   2 - Execute o comando: `docker-compose up`
   
   3 - Abra o browser e acesse: [http://0.0.0.0:3001/products](http://0.0.0.0:3001/products)  
     
   
   Neste exemplo estamos utilizando o endpoint products, mas isso vai depender de cada projeto.
   
   
   
   Veja na imagem um exemplo de arquivo .json contendo duas rotas, product e rota2. 
   
   Cada chave de uma lista será um endpoint.
   
   ![Screenshot from 2021-06-10 12-56-49](https://user-images.githubusercontent.com/42916479/121558873-6a6e2400-c9ec-11eb-9b93-b51072578744.png)

   


   comando para parar o processo `docker-compose down`
   
**Observação:** 
    Se der algum erro na hora de parar o processo, tente executar o comando: 
    `sudo aa-remove-unknown`



### OU SE PREFERIR RODAR SEM O DOCKER ###


   1 - Entre na pasta api-json-server
   
   2 - `npm install`
   
   3 - `npm start`
   
