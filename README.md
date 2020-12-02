# Rendertron

[![CI](https://github.com/GoogleChrome/rendertron/workflows/CI/badge.svg)](https://github.com/GoogleChrome/rendertron/actions)
[![NPM package](https://img.shields.io/npm/v/rendertron.svg)](https://npmjs.org/package/rendertron)

> Rendertron is a headless Chrome rendering solution designed to render & serialise web pages on the fly.

This is a fork from the official repository. I added a Dockerfile so you can build a Docker image for Rendertron.

### Deploying using Docker

* Build the image from the Dockerfile and tag the image (e.g rendertron):
```
docker build -t rendertron .
```
* Starting the app as a container on a local system. Expose port 3000 externally, mapped to port 3000 inside the container:
```
docker container run -p 3000:3000 rendertron
```
