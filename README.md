# Health check

This mod adds a healthcheck layer to any linuxserver.io image it is added too.

### Environment

Ensure these two environment variables are set either in the containers command line arguments or docker-compose file.

```
    environment:
    - PING_URL: <Url to curl request>
    - DOCKER_MODS: steharris/healthcheck-mod
```
