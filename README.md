# motherfucker-spring-boot-docker
![Oooola}](/images/fuckyeah.png)
# Requirements
* [Docker](https://docs.docker.com/engine/installation/)

Change var group in build.gradle by to docker hub user https://github.com/GloriaPG/motherfucker-spring-boot-docker/blob/master/build.gradle#L22
# Build image
``` bash
$ docker login
$ ./gradlew build buildDocker
```
# Docker RUN

``` bash
$ docker run -p 8080:8080 -t gloriapg/gloria-spring-boot-docker
```
## Song
* [John Lennon - Mother](https://www.youtube.com/watch?v=CEnc3RQE2lg)
