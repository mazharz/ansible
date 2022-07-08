# Ansible workstation automation

To run everything:

```bash
$ ansible-playbook local.yml -i inventory.yml --ask-become-pass
```

To run some specific tags:

```bash
$ ansible-playbook local.yml -i inventory.yml --ask-become-pass -t "this,that"
```
