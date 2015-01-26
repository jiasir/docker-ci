# docker-ci
SHANGPIN CI in Docker

### How to use?
* Run from Docker Hub.
```
docker run -p 8080:8080 --name ci --privileged -d spops/ci
```
* Build local image and run.
```
git clone https://github.com/spops/docker-ci.git
docker build -t spops/ci .
docker run -p 8080:8080 --name ci --privileged -d spops/ci
```