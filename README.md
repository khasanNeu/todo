# Mike's Todo List
A Learning Project


##Goal: A single page todo list application that requires a user to login to add to the list. You will use database migrations, controllers, models, services, dependency injection, VueJS, ES6, PHP7.1, bootstrap-vue, and the like.

Be sure to clone the repo I add to this task and checkout the branch with your name for development. I will include a reasonable gitignore file. These requirements will also be in the readme

- create a laravel project named Todo. Make sure composer install and npm install are both run

- Set the application namespace to Todo from App
- Set an appropriate application key
- Make any configurations necessary in the .env file that the installer creates
- Create an empty database in your local postgres instance of whatever name you want to use
- Run the database migrations to get the database ready for users
- In the app directory, move the User.php model to the Models directory, and insure that the namespace matches in that file. Laravel puts models there by default, and I don't know why, models should go in the Models directory, and then whatever sub directory you want.

Once that setup is done, you will be responsible for creating the todo list on your own, so long as it meets the following requirements:

- The todo list has a login, way to create users without logging in (hint: artisan command)
- The database is modified using migrations, but the design of the database is up to you. You will need to store users, todo items, and any other features you decide to add
- Ensure one model per table, and configure as per documentation
- Optional: Grab a package from packagist and use it in your project
- Create api endpoints that your todo application will use to save, update, and delete todo items
- The look of the list and the method of adding things to the list is up to you. Get creative!!! Have fun with it!!
- Use single file vue components to represent the front end. You will need tograb the the bootstra-vue package, which you can find on npmjs.com
- Create at least one service and one repository class that utilize dependency injection to be created. The controller will use the service and the service will use the repository. The repository will access one and only one table (model) and provide functions to iteract with that model.
- No sql is allowed. Learn to use the Eloquen ORM
- add any other features you'd like! This is a basic project so that you can focus on learning.

- bonus: use phpunit to write some unit tests