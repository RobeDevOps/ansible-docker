Role ansible_docker
=========

Requirements
------------
Ubuntu requires the python-apt package installed on remote hosts.

Role Variables
--------------
Python packages required to use pip 

```
# Centos | Redhat
docker_repository: https://download.docker.com/linux/centos/docker-ce.repo
```

Example Playbook for CentOS | RedHat
----------------

Using variables.

```
- hosts: docker_host
  roles:
      - { role: robedevops.ansible_docker }
```

License
-------

BSD

Author Information
------------------

Roberto Cardenas Isla - email: rcardenas20@gmail.com