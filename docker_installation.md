# Docker-installation

### INSTALL DOCKER ON AMAZON LINUX

```
sudo yum update -y
```
```
sudo yum install -y docker
```
```
sudo service docker start
```
```
sudo systemctl enable docker
```
```
sudo usermod -a -G docker ec2-user
```
```
sudo setfacl -m user:ec2-user:rw /var/run/docker.sock
```
```
sudo service docker status 
```
Note: In 5th and 6th step make sure you are giving correct username. You can replace the username (ec2-user) based
on your current logged in user where you want to install docker.
