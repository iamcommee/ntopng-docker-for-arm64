# ntopng-docker-for-arm64

To solve the problem of styling or cannot login to GUI.

I created this repository to explain what a problem of ntopng on arm64 or other version.

## Problem

The main problem is there is no contenet inside of `/usr/share/ntopng/httpdocs/dist`.

So the solution is just mount dist dir from [official repository](https://github.com/ntop/ntopng-dist) to the container.

## How to run

`docker-compose up -d`
