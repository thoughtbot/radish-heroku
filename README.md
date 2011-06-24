# radish-heroku

Run Radish on Heroku (with Redis To Go!)

## howto

First, you'll need an account with Radish. [Sign up!](http://radishapp.com)

Then, fork this repository, and run:

    heroku create YOURAPP-radish --stack cedar

    heroku config:add RADISH_KEY=[YOUR RADISH API KEY] REDIS_URL=[YOUR REDIS URL]

    git push heroku master

Watch the stats roll into Radish!
