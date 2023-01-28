# Groups 


## Groups é de comer ?

O Groups é utilizado para gerenciar permissões do usuário no sistema.
O Comando `$ groups` mostra em quais grupos o seu usuário atual que você esta logado pertence.

```
groups
docker wheel heliezer
```
```
groups
heliezergoncalves sudo
```

## Adicionando usuário a um grupo.

`$ sudo usermod -aG <name_group> <name_user>`

A flag `-aG` diz para adicionar o usuário em `<name_user>` no grupo `<name_group>`. 


Uma situação muito comum é estar logado em servidor linux e necessitar de permissão sudo para executar um comando administrativo.

```
$ docker ps
Got permission denied while trying to connect to the Docker daemon socket at unix:///var/run/docker.sock: Get "http://%2Fvar%2Frun%2Fdocker.sock/v1.24/containers/json": dial unix /var/run/docker.sock: connect: permission denied

```

```
$ sudo docker ps
CONTAINER ID  IMAGE  COMMAND  CREATED  STATUS  NAMES
```



