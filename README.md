# docker-Java-kubernetes-project
Deploying Java Applications with Docker and Kubernetes

-- ferramentas --
- docker 
- kubernetes -> minikube
- linux ubuntu -> java / maven
- git

1 - step git 

git clone from repository 

2 - step install the tools and build docker

mvn clean install
- crear the folder 'target'
docker build -t  silvio69luiz/shotfront:latest .

mvn clean install
- crear the folder 'target'
docker build -t  silvio69luiz/productcatalogue:latest .

mvn clean install
- crear the folder 'target'
docker build -t  silvio69luiz/stockmanager:latest .

3 - step login to docker
https://hub.docker.com/
Log in to your own account
= docker push to repository docker
- docker push silvio69luiz/shotfront:latest
- docker push silvio69luiz/productcatalogue:latest
- docker push silvio69luiz/stockmanager:latest
