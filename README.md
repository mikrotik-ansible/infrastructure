Role Name
=========

A brief description of the role goes here.

Requirements
------------

```
apt-get install sshpass pwgen
```

Startup
------------
```
ansible-playbook ansible-provision.yml
```

Important!!!
------------
Sometimes if you define user for example ansible to run some scripts you must use ansible+c that disable colors on mikrotik console (not sure if is required)

Don't forget put into ansible.cfg
```
hash_behaviour = merge
```
