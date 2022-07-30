Ansible Lighthouse
=========

Simple role to download and unpack Lighthouse

Requirements
------------

Lighthouse must be run inside any webserver. You must install it by yourself

Role Variables
--------------

There are very little variables:

1. Directory where Lighthouse is going to be installed in
```yaml
lighthouse_install_directory: "/etc"
```

2. Name of Lighthouse repo branch that is going to be cloned
```yaml
lighthouse_version: master
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- name: Install lighthouse
  hosts: lighthouse
  vars:
    lighthouse_install_directory: /etc
  roles:
    - lighthouse
```

There is no example tasks to deploy requirement components

License
-------

BSD

Author Information
------------------

The role is created by Netology Student as a homework by Igor Soldatov.
