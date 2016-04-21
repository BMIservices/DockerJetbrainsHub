# Jetbrains Hub
Docker image: Alpine Linux 3.3- openJAVA JRE 8- Jetrbains Youtrack 6.5

Hub is a system that provides centralized authentication, authorization; users, groups, permissions and project management across multiple installations of JetBrains team collaboration tools.

##Usage

Pull the image, create a new container with your data in volumes and start it:

'''bash
docker pull boutch/jetbrains-hub
docker create --name jetbrains-hub -p 8080:8080 -v /srv/jetnraons-hub:/var/lib/hub --restart=always boutch/jetbrains-hub
docker start jetbrains-hub
```
