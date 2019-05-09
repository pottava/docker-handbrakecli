# Dockerized [HandBrake CLI](https://handbrake.fr/)

[![pottava/handbrake](http://dockeri.co/image/pottava/handbrake)](https://hub.docker.com/r/pottava/handbrake/)

## Supported tags and respective `Dockerfile` links

・latest ([versions/0.10/Dockerfile](https://github.com/pottava/docker-handbrakecli/blob/master/versions/0.10/Dockerfile))  
・0.10 ([versions/0.10/Dockerfile](https://github.com/pottava/docker-handbrakecli/blob/master/versions/0.10/Dockerfile))  

## Usage

```console
docker run --rm -v $(pwd):/work pottava/handbrake:0.10 -i VIDEO_TS -o out.mp4
```
