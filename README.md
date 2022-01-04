# Transmission in a Docker Compose
## Introduction
This repository contains a Docker compose file for running Transmission. It contains a sample file with some variables that can be changed to your liking.

## Preparation
The `docker-compose.yml` file can be downloaded and placed on a location of your liking. Make sure to have a separate folder for the configuration files and a place to store your downloads.

## Starting It Up
You can launch the file with `docker-compose up`. After it has finished starting, which should not take very long, you can go to your browser and check if it is running properly.
You can check by going to `127.0.0.1:9091` if you're on the same machine. Replace `127.0.0.1` with the ip address in question if you have it hosted on another machine

After you are sure that it all works, you can keep Transmission running in the background, just run `docker-compose up -d`.

## For More Information
For a more in depth guide on how this works, you can go to (selfhosted.com)[https://selfhostedheaven.com/posts/20210104-transmission-docker-compose/].
