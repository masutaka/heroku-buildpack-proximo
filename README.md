# heroku-buildpack-proximo

**:warning: This is an unofficial Heroku Buildpack.**

Heroku Buildpack to install [proximo](https://devcenter.heroku.com/articles/proximo#installing-the-proximo-wrapper)

`proximo` is the Proximo wrapper. It's related to [Heroku Add-on Proximo](https://devcenter.heroku.com/articles/proximo).

## How it works

Installs from official [proximo binary](http://downloads.proximo.io/proximo-stacklet.tgz).

`proximo` installation ends in `/app/bin` directory.

## Configure from CLI

```
$ heroku buildpacks:add https://github.com/masutaka/heroku-buildpack-proximo.git
```

## Configure from app manifest

```json
{
  "buildpacks": [
    {
      "url": "https://github.com/masutaka/heroku-buildpack-proximo.git"
    }
  ]
}
```
