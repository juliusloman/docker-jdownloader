# docker-jdownloader

Docker image for JDownloader2.

# Running image

Run this image by executing:
    docker run -ti --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix  -v ~/Downloads/:/download  lomo/jdownloader
