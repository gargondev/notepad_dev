# Groups 


## Are Groups edible?

Groups are used to manage user permissions in the system. 
The $ groups command shows which groups your currently logged-in user belongs to.

```
groups
docker wheel heliezer
```
```
groups
heliezergoncalves sudo
```

## Adding a user, a group.

`$ sudo usermod -aG <name_group> <name_user>`

The flag `-aG` say to add the user in `<name_user>` at group `<name_group>`. 

A widespread situation is a user in Linux Server needs privileges to make a sudo command. 

```
$ docker ps
Got permission denied while trying to connect to the Docker daemon socket at unix:///var/run/docker.sock: Get "http://%2Fvar%2Frun%2Fdocker.sock/v1.24/containers/json": dial unix /var/run/docker.sock: connect: permission denied

```
First create the group docker.

`sudo groupadd docker`


Add your user to the docker group.

`sudo usermod -aG docker ${USER}`

Maybe you need to log out and back in, for the group membership re-evaluated and accepted.

```
$ sudo docker ps
CONTAINER ID  IMAGE  COMMAND  CREATED  STATUS  NAMES
```



