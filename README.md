# Container House Keeping
A docker-compose.yml to run housekeeping containers for assisting in systems management tasks

## [watchtower](https://github.com/v2tec/watchtower)

Watchtower is a container for automatically updating running containers
Features include:
* selectively watching containers
* remote hosts
* secure connections
* updating iteself
* Notifications via email
* Notifications through Slack webhook
* Notifications via MS Teams via incoming webhook

## [docker-gc](https://github.com/spotify/docker-gc)

Docker-gc is a garbage collection of container and images

* Dry Run

```
docker run --rm -v /var/run/docker.sock:/var/run/docker.sock -e DRY_RUN=1 spotify/docker-gc
```

* Execute with default cleanup plan

```
docker run --rm -v /var/run/docker.sock:/var/run/docker.sock spotify/docker-gc

```
