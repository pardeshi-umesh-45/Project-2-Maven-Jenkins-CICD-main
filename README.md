<<<<<<< HEAD
Servlet example with corresponding Dockerfile

Use Maven Build first to create war file in Target folder.

mvn clean package

Artifact will be created in target folder.

docker build -t mavenbuild .

Once this is done u will be see image using docker image

Use below command to run the container

docker run -d -p 8080:8080 --name dockercontainer mavenbuild
=======
# Project-2-Maven-Jenkins-CICD-main
>>>>>>> 0ea8c53b57e926011fb026984cb9b10a4e0590a3
