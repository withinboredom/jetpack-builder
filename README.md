# jetpack-builder

Builds Automattic's Jetpack

# Usage

From root of jetpack repo:

```bash
docker run -it -v $PWD:/jetpack -w /jetpack --rm withinboredom/jetpack-builder yarn build
```
