# netlify-website

[![Netlify Status](https://api.netlify.com/api/v1/badges/7598b99b-e73e-433f-a565-4d4d5a774a59/deploy-status)](https://app.netlify.com/sites/sad-feynman-12d3e1/deploys)

> My astounding Nuxt.js project

## Build Setup

``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

## Netlify Deployment

Fairly straightforward and only required two steps (once you connected your GitHub account etc)

1. Add the `yarn generate` command and specify the `dist` folder which is the output of the static site
1. Configure the CNAME record to point your domain to the netlify hosted subdomain.