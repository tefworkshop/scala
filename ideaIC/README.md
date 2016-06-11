docker pull  tefworkshop/scala:ideaIC
docker run -ti --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix tefworkshop/scala:ideaIC
