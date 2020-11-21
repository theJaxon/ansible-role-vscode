Ansible Role: VSCode
=========

![Ansible Role](https://img.shields.io/ansible/role/51380?color=00C5A0&logo=Ansible&style=for-the-badge)
![VSCode](https://img.shields.io/badge/-VSCode-00C5A0?style=for-the-badge&logo=Visual%20Studio%20Code)

Install [Visual studio code](https://code.visualstudio.com/) on different platforms.

### Supported platforms

|     Name    	|    Version    	|
|:-----------:	|:-------------:	|
| RHEL/CentOS 	|       8       	|
|    Fedora   	|       32      	|
|    Ubuntu   	| 20.04 [Focal] 	|
|  Archlinux  	|      all      	|
|   Windows   	|       10      	|
|    MacOS    	|     Mojave    	|


---

Requirements
------------

- On Windows **`Chocolatey`** must be installed
- On MacOS **`Homebrew`** must be installed

Example Playbook
----------------

```yml
- hosts: all
  roles:
    - vscode
```

License
-------

GPL

Author Information
------------------

Created by [theJaxon](https://github.com/theJaxon)
