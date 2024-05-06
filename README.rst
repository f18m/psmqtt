===============
About this fork
===============

This fork exists only to make PSQMTT compatible with old docker clients like the docker version that is
available on the TerraMaster TOS 4.x operating system.
Please see upstream project for all details.

This project is meant to be synched to upstream. Then a single-arch docker image can be pushed
to the Github Container Registry by using::

   docker buildx build --platform linux/arm64 --tag ghcr.io/f18m/psmqtt:1.0.0 --build-arg USERNAME=root --push .

(remember to update the tag version)

