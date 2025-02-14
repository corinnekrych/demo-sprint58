Sample go app with docker build


# Build & Run
## GHA CI
Once CI run successfully you can pull/run the artifact published to DockerHub with:
```
docker run corinnekrych/demo-sprint58:main 
```
## Docker build
```
> docker build -t corinnekrych/demo-sprint58 .
```
## Docker run
```
> docker run corinnekrych/demo-sprint58
Hello, world!
```