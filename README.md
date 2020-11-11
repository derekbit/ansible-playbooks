# Ansible Books

## Install
- CentOS 7
```
sudo yum install -y epel-release
sudo yum install -y ansible ansible-lint
```

## How To Check Playbooks
```
ansible-lint /path/to/your/playbook
```

## Run
```
ansible-playbook --ask-become-pass /path/to/your/playbook
```
