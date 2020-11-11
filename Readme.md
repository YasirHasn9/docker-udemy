## Docker

what is docker ?
it is a container technology for creating and managing containers

---

## container

## what is container ?

unit of software code --> a package of code and dependencies to run that code nodejs + runtime
front-end and backend both of them can be in different container.
u can think of it as a small packages for your web, node and whatever it is and also the
entire environment to run that app

## **_ note _**

if you want to learn docker there 2 core concepts about docker: images and containers.
images are blueprint for containers

---

## image

images are the one who contains the code and the required tools to execute the code
but the containers who runs the code

---

in other words , we can have one image and multiple containers. for example,if we have nodejs web server app ,we can define the image once but run it on different machine and different servers.

so the image that sharable package with all the setup instructions and all the code. and the
containers will be the concrete running instance of the such an image. so containers are based on images.

## create an image:

## there is 2 ways

of creating an image either by built-in by a colleague or one of the images shared by the community and you can found at <a href=""> docker hub </a>

**_ note _**
we can get the one from the community(docker hub) through run the command line
\$ docker run node
now we created a container.
but this container not doing that much. node is a just software you could say.
and now we execute node to get interactive shell where we can insert a commend for docker
but by default a container is isolated from the surrounding environment
