
1 - Criar o package.json dentro da pasta backend
$ npm init -y

2 - instalar o json-server
$ npm i json-server

3 - Criar o arquivo db.json com as seguintes informações. 
{
  "products": [
    {
      "id": 1,
      "name": "Caneta Azul",
      "price": 2.99
    },
    {
      "id": 2,
      "name": "notebook Acer",
      "price": 12000.89
    },
    {
      "id": 3,
      "name": "Sansung S20",
      "price": 5000.89
    }
  ]
}

4 - Nos scripts do  package.json adicionar a linha abaixo na sessão script.
"start": "json-server --watch db.json --port 3001"












