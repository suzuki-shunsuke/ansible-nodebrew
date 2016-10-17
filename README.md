nodebrew
=========

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-nodebrew.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-nodebrew)

Install nodebrew.

https://galaxy.ansible.com/suzuki-shunsuke/nodebrew/

Limitation
-----------

This role will install only on ssh's user.

https://docs.ansible.com/ansible/become.html#becoming-an-unprivileged-user

Requirements
------------

* perl
* curl or wget

Role Variables
--------------

* nodebrew_nonroot: Whether the remote_user is root or not. This variable is set automatically, and is used to execute tasks with the become option.

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - suzuki-shunsuke.nodebrew
```

License
-------

MIT
