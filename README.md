 
# Heroku .NET Core Buildpack

https://github.com/jincod/dotnetcore-buildpack


# Deploy Step

heroku login
heroku create hellomvcheroku
heroku git:remote -a hellomvcheroku
heroku buildpacks:set https://github.com/jincod/dotnetcore-buildpack#v3.1
git push heroku master

最後打開網址 
https://hellomvcheroku.herokuapp.com/
就可以看到網站了

