setup-ansible-host
=========

A generic role to setup the basics of an Ansible controller server

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```
- name: 'Initalize an ansible server'
  hosts: ansible
  become: true
  tasks:
    - name: "Run general setup for the ansible host"
      import_role:
        name: setup-ansible-host
```

License
-------

MIT
