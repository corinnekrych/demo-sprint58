Sample go app with docker build


# Build & Run
## GHA CI
Once CI run successfully you can pull/run the artifact published to [DockerHub](https://hub.docker.com/repository/docker/corinnekrych/demo-sprint58/tags) with:
```
docker run corinnekrych/demo-sprint58:main 
```
This repo is associated to PreProd component [demo-sprint58](https://saas-preprod.beescloud.com/orgs/cloudbees-preprod/components/workflows?componentId=1541ff41-3361-4159-b594-27142bd69baf) with `componentId=1541ff41-3361-4159-b594-27142bd69baf`
## Docker build
```
> docker build -t corinnekrych/demo-sprint58 .
```
## Docker run
```
> docker run corinnekrych/demo-sprint58
Hello, world!
```