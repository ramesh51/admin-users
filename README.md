# admin-users

Creates admin users accounts, based on a configuration data structure.

## Tasks

Everything is in the `tasks/main.yml` file.

## Available variables

The variable `admin_users` must be a "dict" of one or more users :

```
admin_users:
  foo:
    name: foo
    uid: 1001
    fullname: 'Mr Foo'
    password_hash: 'sdfgsdfgsdfgsdfg'
    ssh_key: 'ssh-rsa AZERTYXYZ'
  bar:
    name: bar
    uid: 1002
    fullname: 'Mr Bar'
    password_hash: 'gsdfgsdfgsdfgsdf'
    ssh_key: 'ssh-rsa QWERTYUIOP'
```
