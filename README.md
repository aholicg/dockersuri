modified from [jasonish/suricata:latest](https://github.com/jasonish/docker-suricata)

to build the image:
```bash
$ docker build . -t dockersuri
```

to run the image:
```bash
$ docker run -it dockersuri /bin/bash
```

to copy file from host into container:
1. enter the container
2. from another terminal:
```bash
$ docker cp file <CONTAINER ID>:/home/grey/...
```

to commit changes made to the current container:
```bash
$ docker commit <CONTAINER ID> dockersuri
```
