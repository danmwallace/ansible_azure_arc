Ansible - Azure Arc Role
=========

This role will configure Azure Arc on a target machine. 

Requirements
------------

Target Operating Systems:
* Debian-based operating systems, e.g Ubuntu 22.04 LTS+, Debian 10+
* RHEL-based operating systems, e.g Fedora, Red Hat Linux. (Untested)

Role Variables
--------------

Within `defaults/main.yml` you will find the following Azure-related variables:
```
azure:
  service_principal_id:
  service_principal_secret:
  resource_group:
  tenant_id:
  subscription_id:
  location:
```

Dependencies
------------

* Python 3 + Pip
* Ansible

Example Playbook
----------------

install-arc.yml:

    - hosts: all
      roles:
         - 

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
