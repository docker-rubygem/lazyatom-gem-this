[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/lazyatom-gem-this.svg)](https://hub.docker.com/r/rubygem/lazyatom-gem-this/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/lazyatom-gem-this.svg)](https://hub.docker.com/r/rubygem/lazyatom-gem-this/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/lazyatom-gem-this.svg)](https://hub.docker.com/r/rubygem/lazyatom-gem-this/)
[![Gem Downloads](https://img.shields.io/gem/dt/lazyatom-gem-this.svg)](https://rubygems.org/gems/lazyatom-gem-this/)
# lazyatom-gem-this

Auto-Generated Docker image for lazyatom-gem-this to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/lazyatom-gem-this`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/lazyatom-gem-this`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/lazyatom-gem-this`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/lazyatom-gem-this/)
