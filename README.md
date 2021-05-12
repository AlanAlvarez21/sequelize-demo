# sequelize-demo
Sequelize migrations and seeders demo

$ npx sequelize-cli model:generate --name user --attributes email:string
$ npx sequelize-cli db:migrate

To migrate DB and fill with some data: 

    $ npm run migrate
    $ npm run seeds
