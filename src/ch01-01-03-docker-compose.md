# Managing Docker Compose Services
The Docker containers I've deployed are managed with Docker Compose (`docker compose`). This page will cover basic usage of `docker compose`. For more information, see [the official documentation](https://docs.docker.com/reference/cli/docker/compose/#subcommands).
> *`cd` to the container's folder containing `compose.yaml` before running these (example: `/home/dockeruser/t5server`)*

> *Make sure to remove `<>` from service name*
## Start
### Focused
```
docker compose up <name>
```
### Detached
```
docker compose up <name> -d
```
## Stop
```
docker compose down <name>
```
## Restart
```
docker compose restart <name>
```
## Attach to running container console
```
docker compose attach <name>
```
## Detach from console
Press `Ctrl+p`, then `q` (no ctrl)

Vim binds: `<C-p>q`