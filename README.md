# data-ops

## Heroku Commands

Init session
```
$ heroku login
```

Run the app locally
```
$ heroku local -f Procfile.windows
```

Manual push to heroku branch
```
$ git push heroku main
```

Start (scale up) the app
```
heroku ps:scale web=1
```