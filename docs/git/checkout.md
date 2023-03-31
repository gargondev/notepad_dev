# Comands about git-checkout :fontawesome-brands-github-alt:


## Syntax

```shell
    git checkout [<branch>] 
```

## Links Reference

* [git-sm](https://git-scm.com/docs/git-checkout)
* [Remove Old commits](https://konia.com.br/removendo-lista-de-commits-no-git/)
* [git-orphan-branches](https://shannoncrabill.com/blog/git-orphan-branches/)

## How to remove old commits in git

I have into a situation where the old commits on the master, dont't cant to share history, due to sensitive information in the commit.

### Creating an empty and switch new branch

```shell
    git checkout --orphan [<new_branch>]
```

### Add files

```shell
    git add .
```

### Git Commit

```shell
    git commit -m [<"describe commit">]
```

### Delete branch master or main

```shell
    git branch -D master
```

### Change the name on the current branch for master or main

```shell
    git branch -m master
```

### Send changes to remote repository

```shell
git push -f origin master
```


