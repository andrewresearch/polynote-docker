# polynote-docker
Source for Polynote Spark 3 docker image

Build with:
```
export POLYNOTE_VERSION="0.3.12-2.12-spark3.1.1"
docker build -t andrewresearch/polynote:$POLYNOTE_VERSION --build-arg POLYNOTE_VERSION=$POLYNOTE_VERSION polynote-docker
```
