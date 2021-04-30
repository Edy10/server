# Server do Petshop

## O arquivo db.json contém os dados disponibilizados pelo "servidor" que usaremos no 🐕 [Petshop](https://github.com/Edy10/Petshop).
Para utilizar este arquivo e criar um servidor onde iremos consultar as informações, siga as instruções a seguir:

### Pré-requisitos

Instalar o json-server
Instale a biblioteca do json-server globalmente em seu computador. Ele é o servidor que irá interpretar o arquivo db.json e disponibilizará rotas HTTP para consultarmos. Após instalado, teste o servidor json (na pasta onde estiver o arquivo db.json)

### 🎲 Rodando o db.json (servidor)

## Project setup
```
npm install -g json-server
```

### Compiles and hot-reloads for development
```
json-server db.json
```

Após ativar o servidor, acesse uma das chaves disponibilizadas no arquivo como rota GET (racas, servicos ou produtos) no browser via http://localhost:3000/produtos (confira se ele está rodando na porta 3000). Você deve ver a lista de produtos no browser (pode também testar usando Postman https://www.postman.com/).
