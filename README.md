# k3s-lab

As simple as possible Ansible playbook to bootstrap a k3s cluster.

This playbook runs on a fresh new Ubuntu server setup. It is being
tested on a RPi4 but it will probably work on any plain
Ubuntu Server.

## Inventory

This is a sample of a minimum inventory file. It is not committed in this
repository since each setup will be different in that regard.

```ini
[all]
k3s-master01 ansible_user=ubuntu ansible_host=192.168.1.120
```
