## Deployment steps

### Create an account on Heroku

[Heroku](https://www.heroku.com)

### Download Heroku CLI

[Download and install Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)

### Clone this github repo

```
git clone https://github.com/nikhilkumarsingh/NewsBot.git
```

### Create new Heroku app

Open terminal in project directory and create new Heroku app using this command:

```
heroku create <your-app-name>
```

### Put environment variables in Heroku app

Open **Settings** tab of your Heroku app and set the environment/config variables.

![](http://i.imgur.com/fXNXJhu.png)


### Push to remote Heroku git repo

```
git add .
git commit -m "<your commit message>"
git push heroku master
```
