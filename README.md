# docker-Java-kubernetes-project
Deploying Java Applications with Docker and Kubernetes

-- ferramentas --
- docker 
- kubernetes -> minikube
- linux ubuntu -> java / maven
- git

1- step
git clone from repository 

2- step
mvn clean install
- crear the folder 'target'
docker build -t  silvio69luiz/shotfront:latest .

mvn clean install
- crear the folder 'target'
docker build -t  silvio69luiz/productcatalogue:latest .

mvn clean install
- crear the folder 'target'
docker build -t  silvio69luiz/stockmanager:latest .
