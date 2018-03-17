Libvirt
=========

Manages KVM/QCOW VMs on Linux

Requirements
------------

`libvirtd` and `virsh` should be installed on your system.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```yml
- hosts: servers
  roles:
     - { role: Lowess.libvirt }

```

License
-------

BSD

Author Information
------------------

This role was created in 2018 by [Florian Dambrine](http://floriandambrine.com/), used in [DevOps-360 Automation](http://slides.com/floriandambrine/devops360) course.