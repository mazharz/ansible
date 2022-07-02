# Ansible workstation automation

To run local repo:

```bash
$ sudo ansible-pull --url ~/.ansible/
```

Don't worry about permissions. In files that populate configs (for ex) it becomes your own user to prevent messing up permissions and ownerships.

To run some specific tags:

```bash
$ sudo ansible-pull --url ~/.ansible/ --tags "this,that"
```
