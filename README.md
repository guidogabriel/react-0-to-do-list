# Projetinho de uma to do list básica em react

Com base no vídeo do Matheus Battisti a partir do min 56:30: https://youtu.be/pOVyVivyfok?t=3396

![tela inicio](/arquivos/tela_inicio.png)

## Rodar o Projeto

- Clonar
- `npm install` pra instalar as dependencias
- `npm run server` pra subir o servidor fake na porta 5000
- Em outro terminal, executar `npm start`  pra subir a aplicação.

## Resumo do que foi feito no projeto

npm i json-server - pra simular uma api (servidor ficticio)

npm i react-icons

Adicionar o trecho abaixo no package.json na propriedade scripts
```
"server": "json-server --watch data/db.json --port 5000"
```
Criar um arquivo em `data\db.json` com um json vazio:
```
{

}
```

`npm run server` vai rodar um servidor ficticio na porta 5000 lendo o que tem na pasta data/db.json

