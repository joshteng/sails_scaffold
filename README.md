# Sails.js Barebone App
### a Sails application with basic user model and authentication

** note: application is configured to use MongoDB. Feel free to switch it to your database of choice at config/adapters.js **

Set up
------
1. Configure your database and change package.json to the relevant database adapter
2. Install packages with "npm install"
3. Start your database "mongod"
4. To start the app, just run "sails lift"
5. Go to "http://localhost:1337"


To use MongoDB
------
1. Install MongoDB locally by running 'brew update && brew install mongodb' and then start it 'mongod' **make sure to configure your adapter settings in adapters.js**
2. Or use a hosted service like mongoHQ and link it to by configuring config/adapters.js


Useful Tools
------
1. Genghisapp - if you use mongoDB, simple beautiful admin for your database on your browser [http://genghisapp.com/](http://genghisapp.com/)