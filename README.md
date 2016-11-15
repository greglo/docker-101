Docker 101
==========

> A wildly brief overview, since the online docs and guides are incredibly good.

Docker is a tool to help us build and ship applications

Download / build **Images**

Create **Containers** based off of images

They’re not VMs

They’re not “lightweight VMs”

Google is your friend here

1. `docker images` lists information about your images
1. `docker ps` Lists information about your containers
1. `docker run` Runs an image 
   - `docker run docker/whalesay cowsay Howdy` runs the whalesay image
   - `docker run -it busybox` runs the busybox image in interactive + pseudoterminal mode
