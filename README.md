# Linux image based on node with GoogleChrome/puppeteer support

## Includes:

- chrome requirements for running [puppeteer](https://github.com/GoogleChrome/puppeteer)
- git support for cloning support

## Versions:

- pionl/node-puppeteer-ready:8
- pionl/node-puppeteer-ready:9
- pionl/node-puppeteer-ready:lastest (node 9)

```docker
FROM pionl/node-puppeteer-ready:8
```

## Contribution

1. Change the `Dockerfile.template`
2. Edit `build.sh` if new version is added
3. Run `build.sh` to build images
4. Run `build.sh deploy` to build and push images
