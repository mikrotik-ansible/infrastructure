Role Name
=========

A brief description of the role goes here.

Usage
------------
```
git clone --recursive https://github.com/mikrotik-ansible/infrastructure.git
ansible-playbook install-roles.yml
```
Or
------------
git clone https://github.com/mikrotik-ansible/infrastructure.git




------------
```
ansible-playbook ansible-provision.yml
```

Important!!!
------------
Sometimes if you define user for example ansible to run some scripts you must use ansible+c that disable colors on mikrotik console (not sure if is required)

Don't forget add into ansible.cfg:
```
hash_behaviour = merge
```
