# Dockerized [HandBrake CLI](https://handbrake.fr/)

[![pottava/handbrake](http://dockeri.co/image/pottava/handbrake)](https://hub.docker.com/r/pottava/handbrake/)

## Supported tags and respective `Dockerfile` links

・latest ([versions/1.2/Dockerfile](https://github.com/pottava/docker-handbrakecli/blob/master/versions/1.2/Dockerfile))  
・1.2 ([versions/1.2/Dockerfile](https://github.com/pottava/docker-handbrakecli/blob/master/versions/1.2/Dockerfile))  

## Usage

```console
docker run --rm -v $(pwd):/work pottava/handbrake:1.2 -i VIDEO_TS -o out.mp4
```
