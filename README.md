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
sudo service docker status  or systemctl status docker
```
Note: In 5th and 6th step make sure you are giving correct username. You can replace the username (ec2-user) based
on your current logged in user where you want to install docker.



![1](https://github.com/SandeepKomal/Docker/assets/99358567/cb406a6a-ae5f-4ffa-92f9-3371e39ef888)

![2](https://github.com/SandeepKomal/Docker/assets/99358567/23c68285-0043-4bb8-a7a4-7536e85c00df)

![3](https://github.com/SandeepKomal/Docker/assets/99358567/0e2d7baa-d15b-48c7-8a0d-8833ccdd9f21)

![4](https://github.com/SandeepKomal/Docker/assets/99358567/a359473b-4ff4-494e-8b21-ea1c25261475)

![5](https://github.com/SandeepKomal/Docker/assets/99358567/e4cf3416-04ad-44cc-9e8f-4323f7481a1a)

#### Some Important Git commands  

![1](https://github.com/SandeepKomal/Docker/assets/99358567/30917834-35a2-4091-a0f4-63986ec02447)

![2](https://github.com/SandeepKomal/Docker/assets/99358567/12763fd7-e1b3-4a71-8c03-a98e3af0906f)

![3](https://github.com/SandeepKomal/Docker/assets/99358567/45914b6b-caff-433e-b76c-2c400b292d2b)

![4](https://github.com/SandeepKomal/Docker/assets/99358567/13cf25ea-4b56-42c7-9a81-458ab8ca35d9)
