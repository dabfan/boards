# Install

### Docker engine

* [Mac OS](https://docs.docker.com/docker-for-mac/install/)
* [Windows](https://docs.docker.com/docker-for-windows/install/)
* [Ubuntu](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/)
* [Debian](https://docs.docker.com/engine/installation/linux/docker-ce/debian/)
* [CentOS](https://docs.docker.com/engine/installation/linux/docker-ce/centos/)
* [Fedora](https://docs.docker.com/engine/installation/linux/docker-ce/fedora/)
* [Binaries](https://docs.docker.com/engine/installation/linux/docker-ce/binaries/)

### docker-compose

```bash
sudo curl -s https://raw.githubusercontent.com/titanium-codes/boards/master/DevOps/Docker/scripts/docker-compose > /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

### Final steps

```bash
sudo groupadd docker
sudo usermod -aG docker $USER
sudo systemctl enable docker
```
