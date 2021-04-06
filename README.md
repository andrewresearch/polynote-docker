# polynote-docker
Source for Polynote Spark 3 docker image

Build with:
```
export POLYNOTE_VERSION="0.4.0"
docker build -t andrewresearch/polynote:0.4.0-2.12-spark3.1.1 --build-arg POLYNOTE_VERSION=$POLYNOTE_VERSION polynote-docker
```
