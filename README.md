# sequelize_passport

I took a working sequelize passport file and added in pseudo code to explain what is happening in each file. In summary:


Within the root folder you will have three things: your server.js file, a folder named api, and a folder named config. The server.js file is where your node server startup code will live. I

This file will start you off using express for routing, it will start up your node server on port 3000 or if you’re hosting on heroku the process.env.port will get called by them, and then it requires files from your api and config folders.

Inside of the config folder is where you will store your database configurations, API tokens, etc. 

Inside the routes folder we are equiring our models and passport as we've configured it, and importing our data. Then grabbing all the models and returning them in the response. 

The models define the different columns for a table called. Also note, that in the last line we are exporting User. This means we will have access to this code through the variable User.

The public folder contains the front end html css and javascript files


