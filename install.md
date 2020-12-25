# SET UP THE REPOSITORY
- Update the apt package index and install packages to allow apt to use a repository over HTTPS:
> $ sudo apt-get update

> $ sudo apt-get install \apt-transport-https \ca-certificates \curl \gnupg-agent \software-properties-common

- Add Docker’s official GPG key:
>$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

> $ sudo apt-key fingerprint 0EBFCD88
# INSTALL DOCKER ENGINE
> $ sudo apt-get update

>  $ sudo apt-get install docker-ce docker-ce-cli containerd.io

> $ apt-cache madison docker-ce

>$ sudo apt-get install docker-ce=<VERSION_STRING> docker-ce-cli=<VERSION_STRING> containerd.io

> $ sudo docker run hello-world