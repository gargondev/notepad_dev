# MarkDown


## O que é [:octicons-markdown-16:](https://www.markdownguide.org/) ?
Linguagem de marcação para criação de textos simples, podemos comparar com html porem com uma sintaxe bem mais simples.

## Markdown no Mkdocs Tipos

O Markdown tem basicamente duas padronizações diferentes com pequenas sutilezas entre elas podemos dizer que existe um modelo [padrão](https://www.markdownguide.org/basic-syntax/) e um [estendido](https://www.markdownguide.org/extended-syntax/).

!!! tip "Padrão"

    === "Cabeçalho"

        ``` markdown
        # Título
        ## SubTítulo
        ### h3
        ```
    === "Código"

        ```markdown
        `xpto=1`
        ```
    === "Citação"

        ```markdown
        > Citação de Código
        ```
    
    === "Images"

        ```markdown
        ![nome imagem](./minha_image.jpg)
        ```

    === "Itálico"

        ```markdown
        *em intálico*
        ```
    === "Links"

        ```markdown
        [DuckDuckGo](https://ddg.gg)
        ```
    
    === "Lista ordenada"

        ``` markdown
        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci
        ```
    === "Lista não ordenada"

        ``` markdown
        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci
        ```

    === "Negrito"

        ``` markdown
        **texto em negrito**
        ```



!!! example "Estendido"

    === "Code Block"

        ```markdown
            ```
            def funcao():
            return True
            ```
        ```
    === "Tabelas"

        ``` markdown
         | Nome | Idade |
         | ---- | ----- |
         | Heliezer | 39 |
         | Fausto   | 20 |
        ```

    === "Lista de tarefas"

        ``` markdown
        - [ ] Fazer Compras
        - [x] Escrever Artigo
        - [ ] Pedir Pizza
        ```

    === "Emoji"

        ```markdown
        :snake: 🐍
        ```

    === "Tachado"

        ```markdown
        ~~tachado~~
        ```
    === "Realçado"

        ```markdown
        ==realçado==
        ```