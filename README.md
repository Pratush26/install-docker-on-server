# Install docker on server
This is a Quick guide repository, about how to install docker in the cloud server
> - At first open the server terminal and reach in the root path and run this commands step by step
```
sudo apt update
```
```
sudo apt upgrade
```
```
sudo apt install docker.io -y
```
```
sudo systemctl start docker
```
```
sudo systemctl enable docker
```
> Then check if docker successfully installed or not
```
docker --version
```
or
```
sudo systemctl status docker
```
> You can also test docker _(optional)_
```
sudo docker run hello-world
```
> This will output
>> Hello from Docker!
```
sudo docker run hello-world
```
### Further you can do this basic set-up
> By default, Docker requires `sudo`.

> Add your user to the docker group:
```
sudo usermod -aG docker $USER
```
```
exit
```
```
