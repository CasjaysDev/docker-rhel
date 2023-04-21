## 👋 Welcome to rhel 🚀  

Custom rhel image based on almalinux with bash and tini installed  
  
  
## Run container

```shell
docker run --name -casjaysdev-rhel casjaysdev/rhel bash
```
  
  
## Install my system scripts  

```shell
 sudo bash -c "$(curl -q -LSsf "https://github.com/systemmgr/installer/raw/main/install.sh")"
 sudo systemmgr --config && sudo systemmgr install scripts  
```

## Get source files  

```shell
dockermgr download src casjaysdev/docker-rhel
```

OR

```shell
git clone "https://github.com/casjaysdev/docker-rhel" "$HOME/Projects/github/casjaysdev/docker-rhel"
```

## Build container  

```shell
cd "$HOME/Projects/github/casjaysdev/docker-rhel"
buildx 
```

## Authors  

🤖 casjay: [Github](https://github.com/casjay) 🤖  
⛵ casjaysdev: [Github](https://github.com/casjaysdev) [Docker](https://hub.docker.com/r/casjaysdev) ⛵  
