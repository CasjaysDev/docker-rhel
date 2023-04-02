## 👋 Welcome to rhel 🚀  

rhel README  
Custom rhel image based on almalinux with bash and tini installed  
  
## Run container

```shell
docker run casjaysdev/rhel bash
```
  
  
## Install my system scripts  

```shell
 sudo bash -c "$(curl -q -LSsf "https://github.com/systemmgr/installer/raw/main/install.sh")"
 sudo systemmgr --config && sudo systemmgr install scripts  
```

## Get source files  

```shell
dockermgr download src rhel
```

OR

```shell
git clone "https://github.com/casjaysdevdocker/rhel" "$HOME/Projects/github/casjaysdevdocker/rhel"
```

## Build container  

```shell
cd "$HOME/Projects/github/casjaysdevdocker/rhel"
buildx 
```

## Authors  

📽 dockermgr: [Github](https://github.com/dockermgr) [Docker](https://hub.docker.com/r/casjaysdevdocker) 📽  
🤖 casjay: [Github](https://github.com/casjay) [Docker](https://hub.docker.com/r/casjay) 🤖  
⛵ CasjaysDevDocker: [Github](https://github.com/casjaysdevdocker) [Docker](https://hub.docker.com/r/casjaysdevdocker) ⛵  
