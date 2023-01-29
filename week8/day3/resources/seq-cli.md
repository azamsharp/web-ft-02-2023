
// install sequelize cli globally 

`npm install -g sequelize-cli`

If you are getting permission denied then use the following command: 

`sudo npm install -g sequelize-cli`

// install the sequelize package for your app. 

`npm install sequelize pg --save`

// this will initialize sequelize and create config, migrations, seeders and models // folders

`sequelize init`
`Edit config/config.json. The dialect should be "postgres"`

// run migration to create/update schema of your tables 

`sequelize db:migrate`

// creating a model
 
`sequelize model:create --name User --attributes 'name:string email:string bio:text'`

After creating the model always run sequelize db:migrate so model can be used to create a table.

// creating a new migration

`sequelize migration:create --name 'nameofthemigration'`