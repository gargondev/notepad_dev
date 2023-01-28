# 📚 MkDocs - What do i do, How to do ?


## O que é essa parada ?

O Mkdocs é um gerador de sites estáticos construído em :simple-python:, e que utiliza [markdown](markdown.md) como formato de documentação.
Totalmente personalizável, pode ser hospedado free no [GitHub Pages](https://www.mkdocs.org/user-guide/deploying-your-docs/), no [Readthedocs](https://readthedocs.org/) etc ...



### Cli :octicons-command-palette-24:

A cli do mkdocs é bem simples com os comandos.

!!! tip "CLI"


    === "Help"

        ```shell
        mkdocs -h
        ```

    === "Start do Projeto"

        ```shell
        mkdocs new <nome_do_projeto>
        ```
    === "Servidor Live Server"
        
        ```shell
        mkdocs serve
        ```
    === "Build"

        ```shell
        mkdocs build
        ```
    === "Deploy"

        ```shell
        mkdocs gh-deploy
        ```
### Estrutura básica do projeto :material-file-tree:

O projeto mkdocs básico se divide na arvore abaixo:

```shell
.
├── docs # Diretório para os arquivos .md
│    ├── index.md # Index página inicial.
│   
└── mkdocs.yml # Arquivo de configuração do mkdocs
```
## Referencias

[Doc Oficial](https://www.mkdocs.org/)

### Implementações básicas.

[Video - Rafael Galleani](https://www.youtube.com/watch?v=k7rkjVfuB2M)

[Video - Eduardo Mendes](https://www.youtube.com/live/GW6nAJ1NHUQ?feature=share)




