[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/awsiam/tree/master.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/awsiam/tree/master)
[![](https://github.com/ansible-roles-mamono210/awsiam/workflows/build/badge.svg)](https://github.com/ansible-roles-mamono210/awsiam/actions?query=workflow%3Abuild)

Role Description
=========

Create AWS IAM user with given IAM policy

Requirements
------------

None

Role Variables
--------------

```YAML
---
aws_access_key:
aws_secret_key:
linux_group:
linux_user:
linux_userhome:
awsiam_policy_file_path:
awsiam_policy_name:
awsiam_user:
awsiam_user_state:
aws_regison:
```

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - awsiam
```

License
-------

BSD
