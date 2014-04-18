# Ansible Node.js

Ansible node.js role

* Adds nodejs ppa repository `ppa:chris-lea/node.js`
* Installs nodejs from packages

# Usage

Simply add to server roles list:

```
- hosts: all
  user: root
  roles:
    - nodejs
```