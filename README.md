This buildpack compile the ReactJS frontend code after the backend code is built.


# How to use:
1. `heroku buildpacks:set https://github.com/inscoder-shopify/heroku-compile-fe-buildpack`
2. `heroku config:set FRONTEND_PATH=frontend` pointing to what you want to be a project root.
3. Deploy your project to Heroku.

# How it works
The buildpack takes compile the ReactJS code in the FRONTEND_PATH folder.
