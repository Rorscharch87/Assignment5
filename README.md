# Assignment5 Emanuele Guarascio

----Start the docker----

----Run the terminal----

docker images: List images in the docker

docker ps -a: Show all containers

docker build -t mynodeapp . : Build an image from a Dockerfile -t Name and optionally a tag in the ‘name:tag’ format

docker run --rm -d -p 8888.8888 --name myrunningapp mynodeapp: Run a command in a new container --name Assign a name to the container --rm Automatically remove the container when it exits -d Run container in background and print container ID -p Publish a container’s port(s) to the host

docker logs myrunningapp: Fetch the logs of a container

----Open the browser-----

enter localhost:8888/listBook: Displays a collection of my favorite chinese restaurants

enter localhost:8888/listBook/1 or localhost:8888/listBook/2 or localhost:8888/listBook/3: Displays a single book of the catalog my favorite books

----In the terminal----

(docker rm myrunningapp: Remove one or more containers)

(docker rmi -f mynodeapp: Remove one or more images -f Force removal of the image)
