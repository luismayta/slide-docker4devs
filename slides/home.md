## What is docker?.

Docker is an open source engine that automates the
deployment of any application as a lightweight, portable,
self-sufficient container that will run virtually anywhere.

---

## Why docker?

* Lightweight linux container.
* Boots up in seconds.
* Incrementaly build, revert and reuse your container.
* Api to manage things remotely.

---

## History and capabilities

* Written in go .
* `> 1 year`.
* dot Cloud.
* run self-sufficient containers.
* Amazing speed.
* LightWeight

---

## What is container in docker

---

## Why people developer love docker

### Shipping code to server is easy.

---

### Finding and downloading images

    !bash
    docker search ubuntu
    docker pull ubuntu:14.04

---

### Running

    !bash
    docker run ubuntu:14.04 /bin/echo hello world
    docker run -i -t ubuntu:14.04 /bin/bash