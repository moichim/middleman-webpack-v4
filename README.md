# Simple yet working Middleman & Webpack 4 setup

This repo contains the simpliest possible starting configuration for using Middleman with current (2019) vertion of webpack & stuff.

## Commands

`middleman server` 
Runs Middleman with webpack as an external asset pipeline. Assets are exported into `.tmp/dist`.

`middleman build`
Combines standard Middleman build and the weback assetsinto one `build` folder.

`npm run serve`
Previews the built site on http://localhost:5000.

## File structure
```
assets/          - all assets are managed by webpack
- javascripts/ 
- stylesheets/
- images/
source/
- *.erb - ERB templates managed and served by Middleman
```