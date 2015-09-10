Devhub for Polycademy
=====================

Runs on top of Dokuwiki. Which means it needs writable directories for editing.

The directories that need to be writable are:

```
data
conf
lib/plugins
```

Heroku Deployment:

```sh
heroku login

heroku create devhub-wiki-X

git push heroku master

heroku open

heroku logs
```