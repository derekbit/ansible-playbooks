# Ansible Books

## Install
- CentOS 7
```
yum install -y epel-release
yum install -y ansible ansible-lint

ansible-galaxy collection install ansible.posix
```

## How To Check Playbooks
```
ansible-lint /path/to/your/playbook
```

## Run
```
ansible-playbook --ask-become-pass /path/to/your/playbook
```
