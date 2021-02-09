# Usage

```bash
docker-compose up -d
docker-compose down -d
```

Show list of running containers and assigned GPU:
```bash
dockerps
```

Get an interactive shell in the container:
```bash
dockerexec <container_id> /bin/bash
```



## Build and use image locally

In case you want to build the Docker image manually and locally:
```bash
docker build -t <your_image_tag> <path_to_dockerfile>
```
You can use your local image as outlined above.
