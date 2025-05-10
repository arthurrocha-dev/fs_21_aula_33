#Aula 33

- Sequelize ORM

Instalação

Inicia um repositório node
```
    npm init
```

Instala bibliotecas do sequelize e postgres
```
    npm instal --save sequelize pg pg-hstore
```

Instala biblioteca de desenvolvimento sequelize-cli
```
    npm instal -D sequelize-cli
```
Inicia o projeto sequelize com o sequelize-cli
```
    npx sequelize-cli init
```

Criando a primeiro model de Alunos
```
    npx sequelize-cli model:generate --name Alunos --attributes nome:string
```

Rodar as migrations
```
npx sequelize-cli db:migrate
```

Desfazer última migration
```
npx sequelize-cli db:migrate:undo

```