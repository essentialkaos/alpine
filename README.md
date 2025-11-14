<p align="center"><a href="#readme"><img src=".github/images/card.svg"/></a></p>

<p align="center">
  <a href="https://kaos.sh/w/alpine/cd"><img src="https://kaos.sh/w/alpine/cd.svg" alt="GitHub Actions CD Status" /></a>
  <a href="#license"><img src=".github/images/license.svg"/></a>
</p>

<p align="center"><a href="#usage">Usage</a> • <a href="#contributing">Contributing</a> • <a href="#license">License</a></p>

<br/>

This repository contains Dockerfiles for [Alpine](https://www.alpinelinux.org) 3.19 - 3.22 for automatic image rebuild with the latest packages installed. The resulting images are usually bigger than base images but more secure.

### Usage

Using GitHub Container Registry:

```bash
docker pull ghcr.io/essentialkaos/alpine:3.19
docker pull ghcr.io/essentialkaos/alpine:3.20
docker pull ghcr.io/essentialkaos/alpine:3.21
docker pull ghcr.io/essentialkaos/alpine:3.22
```

Using DockerHub:

```bash
docker pull essentialkaos/alpine:3.19
docker pull essentialkaos/alpine:3.20
docker pull essentialkaos/alpine:3.21
docker pull essentialkaos/alpine:3.22
```

### Contributing

Before contributing to this project please read our [Contributing Guidelines](https://github.com/essentialkaos/contributing-guidelines#contributing-guidelines).

### License

[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)

<p align="center"><a href="https://essentialkaos.com"><img src="https://raw.githubusercontent.com/essentialkaos/.github/refs/heads/master/images/ekgh.svg"/></a></p>
