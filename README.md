In order to run this container you'll need docker installed.

* [Windows](https://docs.docker.com/windows/started)
* [OS X](https://docs.docker.com/mac/started/)
* [Linux](https://docs.docker.com/linux/started/)

### Usage

```shell
docker run -p 9876:80 docker pull ghcr.io/polixis-tech/polixis-qa-task:latest
```

#### Open localhost:9876 in browser

![](image/then-see-me.PNG)


#### Given a simple graph depicted using html canvas the test code should identify and return the following:

1) Number of nodes which do not have an avatar.
2) Number of edges which do not have a relation title.
3) Number of nodes which are not connected to any other nodes.