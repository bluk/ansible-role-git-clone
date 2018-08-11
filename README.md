ansible-role-git-clone
======================

[![GitHub license](https://img.shields.io/github/license/bluk/ansible-role-git-clone.svg)](https://github.com/bluk/ansible-role-git-clone/blob/master/LICENSE) [![Build Status](https://travis-ci.org/bluk/ansible-role-git-clone.svg?branch=master)](https://travis-ci.org/bluk/ansible-role-git-clone)

An [Ansible](https://www.ansible.com) role to clone git repositories to a machine.

Requirements
------------

There are no requirements.

Role Variables
--------------

* `git_repos` - A list of dictionaries of git repositories to clone. Each dictionary should contain a `url` value and a `dest` value.

Dependencies
------------

No dependencies.

Example Playbook
----------------

```
- hosts: servers
  roles:
     - { role: bluk.git_clone }
```

License
-------

Apache 2.0
