heroku-buildpack-graphicsmagick
===========================

Use the latest version of GraphicsMagick (1.3.18) inside Heroku.

## Usage

Note: the order is contrary to instructions, but it works..

```
heroku buildpacks:clear
heroku buildpacks:add https://github.com/lacyrhoades/heroku-buildpack-graphicsmagick
heroku buildpacks:add https://github.com/mcollina/heroku-buildpack-graphicsmagick
git push heroku master
```