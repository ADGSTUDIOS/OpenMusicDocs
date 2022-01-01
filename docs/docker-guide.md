<img src="https://user-images.githubusercontent.com/45560312/128073753-3c84a85e-8de4-4693-97ac-3cc462a18547.png" width="50" height="50">

# Docker Guide

#### Pull Image from the command line

`docker pull ghcr.io/adgstudios/openmusic:main`

#### Default Port Number

`PORT 3000`

#### Running Container - A

provided that you are in the directory you cloned from GitHub

`docker-compose up`

#### Running Container - B

`docker run {image-name}`

#### Use as base image in Dockerfile

`FROM ghcr.io/adgstudios/openmusic:main`