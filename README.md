ansible_role_docker
=========

Ansible role to install docker

Role Variables
--------------
docker_prerequisite_packages: packages required to be installed before installing docker.

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
         - role: respiro.ansible_role_docker

License
-------

MIT / BSD
 