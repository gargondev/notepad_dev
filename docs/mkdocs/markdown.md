# MarkDown


## What is it [:octicons-markdown-16:](https://www.markdownguide.org/)?

It is a markup language you can use to format virtually any document.
We can comparably like HTML, but it has a simple syntax.

## Markdown on the Mkdocs Types.

The Markdown has two different standards, with small changes between them.

* [Basic Syntax](https://www.markdownguide.org/basic-syntax/)
* [Extended Syntax](https://www.markdownguide.org/extended-syntax/)


!!! tip "Basic"

    === "Header"

        ``` markdown
        # Title
        ## Subtitle
        ### h3
        ```
    === "Code"

        ```markdown
        `xpto=1`
        ```
    === "Quote"

        ```markdown
        > Quote of Code
        ```
    
    === "Images"

        ```markdown
        ![name image](./my_image.jpg)
        ```

    === "Italic"

        ```markdown
        *in italic*
        ```
    === "Links"

        ```markdown
        [DuckDuckGo](https://ddg.gg)
        ```
    
    === "Ordered list"

        ``` markdown
        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci
        ```
    === "Unordered list"

        ``` markdown
        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci
        ```

    === "Bold"

        ``` markdown
        **Bold text**
        ```



!!! example "Extended"

    === "Code Block"

        ```python
            ```
            def funcao():
            return True
            ```
        ```
    === "Tables"

        ``` markdown
         | Name | Age |
         | ---- | ----- |
         | Heliezer | 39 |
         | Fausto   | 20 |
        ```

    === "To-do list"

        ``` markdown
        - [ ] Shop Foods
        - [x] Write Article
        - [ ] Improve library documentation
        ```

    === "Emoji"

        ```markdown
        :snake: 🐍
        ```

    === "Strikethrough"

        ```markdown
        ~~Strikethrough~~
        ```
    === "Highlighted"

        ```markdown
        ==highlighted==
        ```