# uzyexe/lita-slack

Run the lita bot for slack

## Dockerfile

[**Trusted Build**](https://registry.hub.docker.com/u/uzyexe/lita-slack/)

This Docker image is based on the [litaio/ruby:2.3.0](https://hub.docker.com/r/litaio/ruby/) base image.

## Using

### docker run

    docker run -d --name="some-redis" --net="host" redis
    docker run -d --name="some-lita-slack" --net="host" --env="SLACK_TOKEN=YOUR_SLACK_TOKEN" uzyexe/lita-slack

--

## lita

[Getting started](http://docs.lita.io/getting-started/)

## lita-slack

[Getting started](https://github.com/kenjij/lita-slack)
