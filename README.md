Ansible Role: System Logging
=========

Ansible role to configure System Logging on Linux Servers.

Requirements
------------

The role does not require anyting to run on RHEL and its derivatives.

Role Variables
--------------

Available variables are listed below, along with default values (see ```defaults/main.yml```):

``` yaml
log_server: "logserver.example.org"
```

```log_server``` **(Required)** The Fully-Qualifed hostname or IP address of the remote logging server.

Role variables can be stored with the hosts.yaml file, or in the main variables file.

Dependencies
------------

None.

Example Playbook
----------------

``` yaml
    - hosts: servers
      roles:
         - role: mikepruett3.logging
```

License
-------

MIT

Author Information
------------------

Role created by [mikepruett3](https://github.com/mikepruett3) on [Github.com](https://github.com/mikepruett3/ansible-role-logging)
