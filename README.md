# An example client for Trengo webhooks in Node.js

1. Deploy the example app.  
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https%3A%2F%2Fgithub.com%2Frleroi%2Ftrengo-webhook-example-node%2Ftree%2Fmain)


2. Create a new webhook on https://app.trengo.eu/admin/developers/webhooks and enter your app URL.  
For example: http://trengo-webhook-example.herokuapp.com/my-endpoint


3. Set the Trengo SIGNING_SECRET in the .env file or in the Heroku settings.  


[![SIGNING_SECRET](https://user-images.githubusercontent.com/6817390/98108779-d3ad1800-1e9c-11eb-8a5a-b12fd3b91208.png)](https://devcenter.heroku.com/articles/config-vars#using-the-heroku-dashboard)


More information:
- https://devcenter.heroku.com/articles/config-vars#using-the-heroku-dashboard
- https://developers.trengo.com/docs/webhooks

