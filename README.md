# docker-ci
CI in Docker

### How to use?
* Run from Docker Hub.
```
docker run -p 8080:8080 --name ci --privileged -d jiasir/ci
```
* Build local image and run.
```
git clone https://github.com/jiasir/docker-ci.git
docker build -t jiasir/ci .
docker run -p 8080:8080 --name ci --privileged -d jiasir/ci
```
