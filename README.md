# Docker
Docker file for firefox gui.
make docker file then
build docker image 
	>docker build -t firefox .
this will make a image named firefox
	>xhost + local:docker                        # this will giveing enveronment
then run command
	>docker run --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix firefox
