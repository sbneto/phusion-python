# phusion-python

This image is based on the official python image

- [`3.7-stretch` (python/3.7/stretch/Dockerfile)](https://github.com/docker-library/python/blob/8601079d1f70b03c01408377716a3243ce75cec9/3.7/stretch/Dockerfile)

As well as on the ubuntu buildpack-deps releases:
- [`stretch-curl` (buildpack-deps/stretch/curl/Dockerfile)](https://github.com/docker-library/buildpack-deps/blob/b0fc01aa5e3aed6820d8fed6f3301e0542fbeb36/stretch/curl/Dockerfile)
- [`stretch-scm` (buildpack-deps/stretch/scm/Dockerfile)](https://github.com/docker-library/buildpack-deps/blob/1845b3f918f69b4c97912b0d4d68a5658458e84f/stretch/scm/Dockerfile)
- [`stretch` (buildpack-deps/stretch/Dockerfile)](https://github.com/docker-library/buildpack-deps/blob/d7da72aaf3bb93fecf5fcb7c6ff154cb0c55d1d1/stretch/Dockerfile)

It puts it all together using `phusion/baseimage` as the base image, trying to keep it as tight as possible.

- [`phusion/baseimage-docker:0.11`](https://github.com/phusion/baseimage-docker)

