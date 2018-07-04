# ElectrumX Server + Bitcore RPC Server Docker Solution

## Requirements

### Docker-CE
Support for the following distribution versions:
* CentOS 7.4 (x86_64-centos-7)
* Fedora 26 (x86_64-fedora-26)
* Fedora 27 (x86_64-fedora-27)
* Fedora 28 (x86_64-fedora-28)
* Debian 7 (x86_64-debian-wheezy)
* Debian 8 (x86_64-debian-jessie)
* Debian 9 (x86_64-debian-stretch)
* Debian 10 (x86_64-debian-buster)
* Ubuntu 14.04 LTS (x86_64-ubuntu-trusty)
* Ubuntu 16.04 LTS (x86_64-ubuntu-xenial)
* Ubuntu 17.10 (x86_64-ubuntu-artful)
* Ubuntu 18.04 LTS (x86_64-ubuntu-bionic)

Download and execute the automated docker-ce installation script - maintained by the Docker project.

```
sudo curl -sSL https://get.docker.com | sh
```

## Deployment of Docker Solution
Login as root, then do:

```
wget https://raw.githubusercontent.com/LIMXTEC/electrumx/master/docker/electrumx-docker.sh
chmod +x electrumx-docker.sh
./electrumx-docker.sh
```