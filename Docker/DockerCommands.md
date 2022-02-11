# Useful Docker commands

Run a container in detached mode, binding port 8080 of the host to port 8080 of the Docker
```sh
$ docker run -d -p 8080:8080 name_of_the_container
```

Get the ID of the container
```sh
$ docker ps
```

Stop a container
```sh
$ docker stop <the-container-id>
```
Remove a container
```sh
$ docker rm <the-container-id>
```

Stop and remove a container
```sh
$ docker rm -f <the-container-id>
```

Create a named volume (think of named volume as simply a bucket of data)
```sh
$ docker volume create <name-of-the-volume>
```

Start an app container but specifying the volume mount (with the flag -v)
```sh
$ docker run -dp 3000:3000 <name-of-the-volume>:<path-to-be-mounted> <name-of-the-container>
```

Get info about the volume
```sh
$ docker volume inspect <name-of-the-volume>
```

Create network of containers
```sh
$ docker network create <name-of-the-network>
```

