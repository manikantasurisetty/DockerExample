# DockerExample
Simple nodejs docker project

This simple app will run through docker.

You need to install docker in your machine ,start the docker and run below coimmands in order to see the applictaion running

Steps:

Build Image command:

docker build -t simple-docker-node-example .

simple-docker-node-example-Can be your own image name

Run your container:

docker run -d -p 3000:80 --name simple-docker-node-example-container -it simple-docker-node-example

simple-docker-node-example-container-Can be your custom container name
simple-docker-node-example-Should be your Image name
-p 3000:80 -Publish your code on 3000 pport from 80 port(optional argument)

With the above setting sin place you can run http://localhost:3000/ to see the basic app running


