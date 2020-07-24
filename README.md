# Setup for ansible
-------------------

### Configure ansible.cfg

make `transport= local` and `host_key_checking = False` in the [default] section.

### Configure hosts

```
[webservers]
127.0.0.1 ansible_user=ubuntu

[all:vars]
ansible_python_interpreter=/usr/bin/python3
```
