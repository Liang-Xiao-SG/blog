---
layout: post
author: liangxiao
---
## Run 
*   **`docker run [IMAGE]`**: Create & start a container.

    *   `-p 80:80` (port map host:container)

    *   `-d` (detached/background)

    *   `--name [NAME]` (give it a name)

*   **`docker ps`**: List running containers.

    *   `-a` (all, including stopped)

*   **`docker stop [ID/NAME]`**: Stop a running container.

*   **`docker start [ID/NAME]`**: Start a stopped container.

*   **`docker rm [ID/NAME]`**: Remove a stopped container.

*   **`docker build -t [NAME]:[TAG] .`**: Build an image from `Dockerfile` in current dir.
## images

*   **`docker images`**: List local images.

*   **`docker rmi [IMAGE_ID]`**: Remove an image.

*   **`docker logs [ID/NAME]`**: View container output.

*   **`docker exec -it [ID/NAME] bash`**: Run command inside container (e.g., shell).

*   **`docker pull [IMAGE]`**: Download an image.

*   **`docker system prune`**: Clean up unused data (containers, images, networks, volumes).


