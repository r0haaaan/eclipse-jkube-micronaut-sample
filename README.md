# Eclipse JKube Micronaut sample

This is a demo project used for my blog on deploying Micronaut application to Kubernetes using Eclipse JKube

## How to Build
```
mvn package
```

## Building and Pushing Docker image to Docker Hub
```
# Configure your dockerhub username in pom.xml

mvn k8s:build k8s:push
```

## Deploying to Kubernetes
```
mvn k8s:resource k8s:apply
```
