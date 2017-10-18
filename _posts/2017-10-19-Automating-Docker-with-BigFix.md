---
published: false
---

## Setup Docker Host

- [Install Ubuntu](https://forum.bigfix.com/t/thin-imaging-and-installing-the-bigfix-agent/15750)
  - Kickstart file
- [Install BigFix](https://github.com/jgstew/tools/blob/master/bash/install_bigfix.sh)
- [Install Docker](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/)
  - Fixlets
  - Baseline
  
## Use Docker Host

- Create Docker [Containers](https://github.com/jgstew/tools/blob/master/bash/docker_bigfix_client.sh)
- Create Docker [Images](https://github.com/jgstew/tools/blob/master/docker/Dockerfiles/bigfix_ubuntu/Dockerfile) -> Containers

## Analize Docker Host & Containers

Most info for Docker Containers is stored as JSON on the Docker Host, which BigFix can read.

- Analyses
- Automatic Groups


### Related:

- https://forum.bigfix.com/t/bay-area-bigfix-user-group-october-19th-2017-emeryville-ca/22323
- https://forum.bigfix.com/t/thin-imaging-and-installing-the-bigfix-agent/15750
- https://github.com/jgstew/tools/blob/master/bash/install_bigfix.sh
- https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/
- https://docs.docker.com/engine/reference/run/
