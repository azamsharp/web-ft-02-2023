# Activity - Sequelize Migration


Create a migration called ```add-image-url-to-dishes``` which will add a new column "imageURL" to the Dishes table. Make sure you implement the Up and Down functions of the migration. 

Run sequelize `db:migrate` to run your migration. 

Check your Dishes table to make sure the imageURL column has been added. 

To create migration file use the following: 

`sequelize migration:create --name 'nameofthemigration'`
