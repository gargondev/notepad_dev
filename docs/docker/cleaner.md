# How Cleaner Docker "unused"


## Remove 

!!! example "Images"

    === "First Mode"

        ```shell
            docker system prune --filter="label=unused"
        ```
    === "Second Mode"

        ``` shell
         docker rmi $(docker images -f "dangling=true" -q)
        ```
