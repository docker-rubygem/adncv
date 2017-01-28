[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/adncv.svg)](https://hub.docker.com/r/rubygem/adncv/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/adncv.svg)](https://hub.docker.com/r/rubygem/adncv/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/adncv.svg)](https://hub.docker.com/r/rubygem/adncv/)
[![Gem Downloads](https://img.shields.io/gem/dt/adncv.svg)](https://rubygems.org/gems/adncv/)
# adncv

Auto-Generated Docker image for adncv to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/adncv`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/adncv`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/adncv`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/adncv/)
