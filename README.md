# graphite-web-ansible
Ansible role to install Graphite-web on Alpine Linux

* Prepare Alpine Linux for Ansible
* Clone this repo
* Prepare a play like this

```
- hosts: graphite01.poznan.tbhydro.net
  roles:
  - graphite-web-ansible
```

* Run:
```
ansible-playbook playname.yml
```
