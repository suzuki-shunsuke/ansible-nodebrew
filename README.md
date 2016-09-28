nodebrew
=========

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-nodebrew.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-nodebrew)

Install nodebrew.

https://galaxy.ansible.com/suzuki-shunsuke/nodebrew/

Requirements
------------

* perl
* curl or wget

Role Variables
--------------

* nodebrew_users: Users who are Installed the nodebrew. The default value is the remote_user.
* nodebrew_nonroot: Whether the remote_user is root or not. This variable is set automatically, and is used to execute tasks with the become option.

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - role: suzuki-shunsuke.nodebrew
    nodebrew_users: ubuntu
```

License
-------

MIT
