# RunDeck

RunDeck in a container

Usage:
Building:

```Docker
docker build . -t rorymurdock/rundeck:latest
```
g81fUhyqv%0B
Running:

```Docker
docker run --name=rundeck -d -v ~/docker/data:/home/rundeck/server/data -v ~/docker/config:/home/rundeck/server/config/ -p 4440:4440 rorymurdock/rundeck:latest
```

If this is your first time running this container you will need to create a `config/realm.properties` so you can login. See the example file in this repo.
