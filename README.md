# Testing how railway deploys work

## Steps

1. [install the railway cli](https://docs.railway.app/develop/cli)
2. `railway login` to login to railway
3. starting in a **(sub)directory** as the deploy target, either:
   - `railway init` to init a new project
   - `railway link` to link to an existing project
4. `railway up` to deploy manually

## Exposing the deploy to the internet

1. access the project's page. e.g `https://railway.app/project/...`
2. from *the service's settings* (not the *project's*), click on **generate domain** or provide a custom one.
