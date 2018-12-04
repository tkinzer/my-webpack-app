

### Heroku

#CLI

Deploy and Configure

8. Deploy a production build to Heroku
If you don’t already have a heroku account, create one here: https://signup.heroku.com/

In your command line, run the following:

heroku login
You will need to type in your heroku credentials to the terminal. Once you have successfully entered your heroku credentials, run the following in your terminal to create a new deployed app:

heroku create sample-webpack-production-app
Replace sample-webpack-production-app with your own app name.

Then push your app build to heroku with the following git in your terminal:

npm install 
yarn install 
git add . 
git commit -m "initial commit"
git push heroku master
These commands install your dependencies and connect your repo to the remote repository hosted by heroku.

Congrats! Now you’ve completed all the necessary steps to deploy a Webpack build. To view your app, run the following in the terminal:

heroku open