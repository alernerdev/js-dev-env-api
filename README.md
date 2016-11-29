# js-dev-env-demo-api
API for JS Dev Env Demo in Pluralsight course

Heroku commands for deployment:
heroku login
heroku create                               --- creates the app on heroku and gives it some random name
heroku git:remote -a lit-everglades-48908   --- places our code into github where heroku knows about it
git push heroku master                      ---- during the push, heroku takes our code from github and deployes it to the url


whenever you make changes, commit them, and then do git push

