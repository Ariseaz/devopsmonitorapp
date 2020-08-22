# devopsmonitorapp
Monitor app using Prometheus

This app is built with nodejs (express engine)

Build image with 
***
_docker build -t forethought ._
***
forethought is just a name tag to the build image, it could be anything

To build container from image
***
_docker run --name ft-app -p 80:8000 -d forethought_
***
