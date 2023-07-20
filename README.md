# any-docker
Dockerized all-in-one instance of an anytype node

Aim: to provide a simple to use all-in-one docker image that runs a Anytype node and required infrastructure.

Single docker image running:

* mongodo
* minio
* redis
* any-sync-tool
* any-sync-coordinator
* any-sync-node
* any-sync-filenode

## Build
```
git clone https://github.com/SamBouwer/any-docker
cd any-docker
docker build -t any-docker .
```

## Run
```
docker run ...
```

# Contribute

I'm building a Dockerfile based on the instructions as posted here: https://tech.anytype.io/how-to/self-hosting

As building Anytype nodes and clients from source for selfhosting is new, and I am personally new to building docker images, any help is welcome!

## Disclaimer

I am not part of the Anytype team.

# TODO
* Improve documentation
* Split monolith Docker image to allow BYOI (bring your own infra; s3, mongodo, redis)
