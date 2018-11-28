# Dockerized and localized Debian 8.0 "Jessie"

Dockerfile definition for a fully `en_US.UTF-8`-localized Debian 8.0 "Jessie" image.

Wheezy has almost the same packages and versions as Ubuntu LTS, while providing a much slimmer image size.

The Docker image is also available for pulling from the [Docker Hub][vsrv]:

    $ sudo docker pull vivaserver/wheezy

[vsrv]: https://registry.hub.docker.com/u/vivaserver/jessie/

## Build

    $ sudo docker build . -t vivaserver/jessie

## License

Released under the [MIT License](http://www.opensource.org/licenses/MIT).

## Copyright

(c)2018 [Cristian R. Arroyo](mailto:cristian.arroyo@gmail.com)
