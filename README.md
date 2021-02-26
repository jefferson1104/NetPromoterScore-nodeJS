## API com nodeJS, ExpressJS & typescript

### Como iniciar um projeto && Dependencias
```bash
# Crie um diretorio, acesse ele e execute
$ yarn init -y

# Instale o ExpressJS
$ yarn add express

# Instale o pacote de tipagem para o nodemodules com typescript
$ yarn add @types/express -D

# Instale typescript no projeto
$ yarn tsc --init

# Instale a dependencia de desenvolvimento que converte typescript para javascript
$ yarn add ts-node-dev -D

# Instalação do typeORM
$ yarn add typeorm reflect-metadata

#Instalação do sqlite3
$ yarn add sqlite3

#Instalação da biblioteca UUID
$ yarn add uuid

#Instalação do pacote de tipagem do uuid
$ yarn add @types/uuid -D   
```

### Endpoints da API
```bash
# Rota para listar conteudo (GET)
http://localhost:3333

# Rota para salvar conteudo (POST)
http://localhost:3333

```

## Banco de dados
```bash
# BANCO DE DADOS: PostgresSQL, MongoDB, MySQL e etc...

# DRIVER PostgresSQL documentação
https://node-postgres.com/

# KnexJS documentação deste query builder
http://knexjs.org/

# TypeORM (usaremos este no projeto)
https://typeorm.io/
```

### TypeORM
```bash
# criando uma migration
$ yarn typeorm migration:create -n NameMigration

# executar todas migrations 
$ yarn typeorm migration:run 

# executar rollback da ultima migration executada
$ yarn typeorm migration:revert 

```