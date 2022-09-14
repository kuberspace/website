# The Kuberspace documentation

This repository contains the assets required to build the [Kuberspace website and documentation](https://kuberspace.io/). We're glad that you want to contribute!

- [Contributing to the docs](#contributing-to-the-docs)
- [Localization ReadMes](#localization-readmemds)

## Using this repository

You can run the website locally using Hugo (Extended version), or you can run it in a container runtime. We strongly recommend using the container runtime, as it gives deployment consistency with the live website.

## Prerequisites

To use this repository, you need the following installed locally:

- [npm](https://www.npmjs.com/)
- [Go](https://golang.org/)
- [Hugo (Extended version)](https://gohugo.io/)
- A container runtime, like [Docker](https://www.docker.com/).

Before you start, install the dependencies. Clone the repository and navigate to the directory:

```bash
git clone https://github.com/kuberspace/website.git
cd website
```

The Kuberspace website uses the [Docsy Hugo theme](https://github.com/google/docsy#readme). Even if you plan to run the website in a container, we strongly recommend pulling in the submodule and other development dependencies by running the following:

```bash
# pull in the Docsy submodule
git submodule update --init --recursive --depth 1
```
