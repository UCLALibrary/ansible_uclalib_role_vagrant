# Vagrant Ansible Role [![Build Status](https://travis-ci.org/UCLALibrary/uclalib_role_vagrant.svg?branch=master)](https://travis-ci.org/UCLALibrary/uclalib_role_vagrant)

This role configures RHEL/CentOS in preparation for it to be packaged as part of a .box file for Vagrant/VirtualBox deployment using [Packer](http://www.packer.io/).

Requirements
------------

This role requires Ansible 1.8 or higher.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Install Vagrant
```
- hosts: all
  roles:
    - { role: uclalib_role_vagrant }
```

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2014 by [Jeff Geerling](http://www.jeffgeerling.com/), author of [Ansible for DevOps](https://www.ansiblefordevops.com/). It has been modified for UCLA Library's purposes.
