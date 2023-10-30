# Ansible Playbooks 


## How to use with Docker

Add the following lines to your DOCKERFILE:
``` dockerfile
RUN apt-get -y update && \
    apt-get install -y git && \
    git clone --branch [version/tag] https://github.com/ktierney15/Ansible-Playbooks.git && \
    cd [path to playbook]
```