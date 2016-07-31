nodebrew
=========

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-nodebrew.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-nodebrew)

Install nodebrew.

https://galaxy.ansible.com/suzuki-shunsuke/nodebrew/

Requirements
------------

Nothing.

Role Variables
--------------

* nodebrew_users: Users who are Installed the nodebrew. The default value is the remote_user.

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - { role: suzuki-shunsuke.nodebrew, nodebrew_users: ubuntu }
```

License
-------

MIT
