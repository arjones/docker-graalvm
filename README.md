# Docker Image for GraalVM
A base image to run apps using [GraalVM](https://www.graalvm.org)

## Build
```bash
VERSION=1.0.0-rc1 && \
  docker build --build-arg GRAALVM_VERSION=${VERSION} -t ${USER}/graalvm:${VERSION} .
```