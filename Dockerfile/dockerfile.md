Creating Docker Images
======================

> There are always more options, read the [excellent docs](https://docs.docker.com/engine/reference/builder/)!

1. Create a Dockerfile
1. Run `docker build .`
1. Run `docker tag  <IMAGE_HASH> <IMAGE_NAME>:<TAG>`


Creating a Dockerfile
---------------------

There are lots of directives you can give to Docker when building an image, but a couple of important ones are

1. Choosing a base image
1. Adding in data from the *context*
1. Exposing ports
1. Setting an entrypoint
