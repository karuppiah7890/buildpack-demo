# buildpacks-demo

Just me trying out [buildpacks](https://buildpacks.io)

## Building docker image for buildpack

```bash
$ # change image name appropriately if needed
$ pack package-buildpack karuppiah7890/demo-ruby-cloud-native-buildpack --config ./ruby-cloud-native-buildpack-package.toml
```

## Pushing buildpack docker image

```
$ docker login
$ # change image name appropriately if needed
$ docker push karuppiah7890/demo-ruby-cloud-native-buildpack:latest
```

