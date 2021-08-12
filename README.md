# Ansible new PC setup playbook

## Introduction
This is a simple playbook I made in order to easily install all the apps I needed. Feel free to fork it and use it

## Configuration
Run the following command before running any playbook
```bash
ansible-galaxy collection install community.general
```
## Usage
### Fedora
```bash
$ ansible-playbook playbook-fedora.yml
```

### Ubuntu-based
```bash
$ ansible-playbook playbook-ubuntu.yml
```
