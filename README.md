# do-api-slugs-vue-docker-nginx-do-app-droplet

# 🚀 Look up slugs for use with the API DigitalOcean 🚀

https://github.com/coding-to-music/do-api-slugs-vue-docker-nginx-do-app-droplet

From / By Andrew Starr-Bochicchio https://github.com/andrewsomething

https://github.com/andrewsomething/do-api-slugs

## Environment variables:

```java

```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/do-api-slugs-vue-docker-nginx-do-app-droplet.git
git push -u origin main
```

# DigitalOcean API Slugs

[https://slugs.do-api.dev/](https://slugs.do-api.dev/)

![Screenhot](https://i.imgur.com/etNCvLU.png)

## Project Details

The frontend is provided by a Vue.js powered static site. The backend Go service found in the `api/` directory. It proxies the DigitalOcean API so that an API token is not required on the frontend and set a `Cache-Control` header so the responses are appropriately cached by the CDN.

### Local Development

A Docker Compose file is provide for local development. To build and run both components, use:

    docker-compose up --build

### Deployment

This app is deployed using DigitalOcean App Platform. An example spec for the deployment can be found at `example-spec.yaml`.
