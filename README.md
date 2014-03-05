# Sails.js Barebone App
### a Sails application with basic user model and authentication

** note: application is configured to use MongoDB. Feel free to switch it to your database of choice at config/adapters.js **

Set up
------
1. Configure your database in config/adapters.js (good to go if you're using mongodb)
2. Change package.json to the relevant database adapter (if you're not using mongodb)
3. Install packages "npm install"
4. Start your database "mongod"
5. Start the app "sails lift"
6. Go to "http://localhost:1337"


To use MongoDB
------
1. Install MongoDB locally by running 'brew update && brew install mongodb' and then start it 'mongod' **make sure to configure your adapter settings in adapters.js**
2. Or use a hosted service like mongoHQ and link it to by configuring config/adapters.js *more instructions in adapters.js **prevent committing sensitive information in your repo. use local.js instead, it's ignored by default (read more at Sails.JS documentation)**


Useful Tools
------
1. Genghisapp - if you use mongoDB, simple beautiful admin for your database on your browser [http://genghisapp.com/](http://genghisapp.com/)