#### docker_intuivo_cli
# Docker Command Line CLI - The missing tool set

For all you docker aficionados(as) there is this library to help you get rid of old/all containers, so you don't have to remember the "psfls..etc" commands
just added then your path

git clone https://github.com/zeusintuivo/docker_intuivo_cli.git

# Usage
Call each script as needed.
They are self descriptive of what they do.

### Example
```Shell
❯ docker-delete-all-volumes
 docker rm $(docker volume ls )
 •  docker rm DRIVER    VOLUME NAME
local     5bf31cdeaab9dab7895f4ca79f5a8916_mysql

Total reclaimed space: 22.66GB
❯
```

