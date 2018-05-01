# jetpack-builder

Builds Automattic's Jetpack

# Usage

From root of jetpack repo:

```bash
docker run -it -v $PWD:/jetpack -w /jetpack --rm withinboredom/jetpack-builder yarn build
```

# What's inside

- [PHP 7.2](https://github.com/docker-library/php/tree/master/7.2/stretch/cli/)
- [Node 9](https://hub.docker.com/_/node/)
