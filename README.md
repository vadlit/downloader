#Downloader
This is a server for downloading of new builds and investigation of their product-info files

## Build docker image with maven
```
mvn compile jib:dockerBuild
```

## Run docker image
```
docker run --rm -it --add-host=host.docker.internal:host-gateway ru.vadlit/ru.vadlit.downloader:latest
```