# Barberlounge - API

## About

 An application that helps customers schedule appointments with  a saloon.


## Getting started

**Cloning the repo**

```
git clone https://github.com/elywin/barberzlounge-api.git

cd barberzlounge-api
```

**Installing dependencies**

```
npm install
```

**Set the environment variables in a _.env_ file as exemplified in the _.env.example_**

**Create the postgres database (you can do it manually as well)**

```
npx sequelize db:create
```

**Run the migrations to create the needed tables**

```
npx sequelize db:migrate
```

**Note:**
run `npx sequelize --help` to see all sequelize can do


**start the server**

```
npm run dev
```
