# phusion-python

This image is based on the official python image

- [`3.6-jessie` (3.6/jessie/Dockerfile)](https://github.com/docker-library/python/blob/f12c2df135aef8c3f645d90aae582b2c65dbc3b5/3.6/jessie/Dockerfile)

As well as on the ubuntu xenial buildpack-deps releases:
- [`xenial-curl` (xenial/curl/Dockerfile)](https://github.com/docker-library/buildpack-deps/blob/d662dc69f910feb241f6d0c9d2cd6cc2fb6c5e6c/xenial/curl/Dockerfile)
- [`xenial-scm` (xenial/scm/Dockerfile)](https://github.com/docker-library/buildpack-deps/blob/2da658b9a1b91fa61d63ffad2ea52685cac6c702/xenial/scm/Dockerfile)
- [`xenial` (xenial/Dockerfile)](https://github.com/docker-library/buildpack-deps/blob/d7da72aaf3bb93fecf5fcb7c6ff154cb0c55d1d1/xenial/Dockerfile)

It puts it all together using `phusion/baseimage` as the base image, trying to keep it as tight as possible.

- [`phusion/baseimage-docker`](https://github.com/phusion/baseimage-docker)

