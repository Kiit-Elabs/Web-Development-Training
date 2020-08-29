# Basic-ToDo-App
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)
[![](https://img.shields.io/badge/python-3.5%2B-green.svg)]()
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)

## Running Locally

Make sure you have:
* [Node.js](http://nodejs.org/)
* [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.
* An account in [MongoDB](https://account.mongodb.com/account/login) and signin for [MongoDB Atlas](https://www.mongodb.com/cloud/atlas). 
* You need to change the username and password in the `app.js` file.

```sh
git clone git@github.com:Lucifergene/Basic-ToDo-App.git
cd Basic-ToDo-App
npm install
node app
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
heroku create
git push heroku master
heroku open
```

Alternatively, you can deploy your own copy of the app using the web-based flow:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)


