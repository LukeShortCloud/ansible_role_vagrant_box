# ansible_role_vagrant_box

Setup a virtual machine image to be used as a [Vagrant](https://www.vagrantup.com/) box. This will create a vagrant user, add the Vagrant SSH public key, lock-down the SSH service, and enable the legacy network interface naming scheme.

## Requirements

Ansible >= 2.8

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```
---
- hosts: new-vagrant-box
  roles:
    - ansible_role_vagrant_box
```

## License

Apache Software License v2.0.
