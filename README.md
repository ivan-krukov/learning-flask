# Flask tutorial

This is a short tutorial for using Flask web application framework.
The only purpose is to keep track of learning how to use Flask.

## Deployment notes

This app is deployed on heroku.
After creating a `heroku` account:

```bash
# login
heroku login

# create ne
heroku create

# enable web application requests
heroku ps:scale web=1

# Push to the repo
git push heroku master

# Magic
heroku open
```

You can check the logs lcoally with:

```
heroku logs
```

Check the running `dyno`s with:
```
heroku ps
```
