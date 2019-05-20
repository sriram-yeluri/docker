# docker
repository created to maintain docker images and documentation


## RHEL Docker images
Pull latest image from redhat registry and spin up a container
```sh
docker pull registry.access.redhat.com/rhel7
docker run -d --name rhel7 registry.access.redhat.com/rhel7 tail -f /dev/null
```
