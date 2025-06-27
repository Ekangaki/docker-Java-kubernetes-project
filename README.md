# docker-Java-kubernetes-project
Deploying Java Applications with Docker and Kubernetes

Credit: https://github.com/danielbryantuk/oreilly-docker-java-shopping/

### Clone the source code
## install maven

## cd productcatalogue -> mvn clean install -> docker build -t ekangaki/productcatalogue:v1 -> docker images 
## docker login -u ekangaki -> Enter Password -> docker push ekangaki/productcatalogue:v1

## cd shopfront -> mvn clean install -> docker build -t ekangaki/shopfront:v1 -> docker images 
## docker login -u ekangaki -> Enter Password -> docker push ekangaki/shopfront:v1

## cd stockmanager -> mvn clean install -> docker build -t ekangaki/stockmanager:v1 -> docker images 
## docker login -u ekangaki -> Enter Password -> docker push ekangaki/stockmanager:v1
