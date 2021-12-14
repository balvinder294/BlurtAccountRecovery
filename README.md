# Blurt Account Recovery

## Website

https://recovery.blurtwallet.com

## Technology

- dHive
- jQuery
- Docker

## Building Image

To build and tag image

```bash
docker build -t tekraze/blurt-recovery:1.0.0 .
```

To run recovery app

```bash
sudo docker run -it --rm -d -p 8080:80 --name blurtrecovery blurt-recovery
```

## Using PreBuilt Image from DockerHub

https://hub.docker.com/r/balvinder294/blurt-recovery

pull image

```
docker pull balvinder294/blurt-recovery:1.0.0
```

To run recovery app

```bash
sudo docker run -it --rm -d -p 8080:80 --name blurtrecovery balvinder294/blurt-recovery
```

## TODO

Currently this tool has minimal validation and UI can be improved too. In next updates I am going to focus on those.

## Contributing

Feel free to fork the repository and submit your changes.


----

Maintained by [@tekraze](https://blurt.blog/@tekraze). Vote for [@tekraze as Witness here](https://blurtwallet.com/~witnesses?highlight=tekraze)
