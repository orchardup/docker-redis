docker-redis
============

**Note:** This image is deprecated. Please use the [official redis image](https://registry.hub.docker.com/_/redis/) instead.

Redis on Docker.

    $ docker run -d -p 6379:6379 orchardup/redis
    $ nc localhost 6379
    incr foo
    :1

