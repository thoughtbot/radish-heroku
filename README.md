# radish-heroku

Run Radish on Heroku (with Redis To Go!)

## How to

First, you'll need an account with Radish. [Sign up!](http://radishapp.com)

Then, fork this repository, and run:

    heroku create YOURAPP-radish --stack cedar

    heroku config:add RADISH_KEY=[YOUR RADISH API KEY] REDIS_URL=[YOUR REDIS URL]

    git push heroku master

Make sure to replace the "YOUR" stuff (your app name, api key, redis url) with your real information. Once that works, watch the stats roll into Radish!

## Need help?

Open up a [new support request](http://help.radishapp.com) if you have any trouble getting this working.
