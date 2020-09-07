# Pop OS playbook

Use Ansible to install and configure software on a laptop with Pop OS.

## Quick Start

### Install Ansible

```
sudo apt update
sudo apt install software-properties-common
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```

### Clone this Repo

```
git clone git@github.com:omero/pop-os-playbook.git
```

### Run

```
cd pop-os-playbook
ansible-playbook --ask-become-pass local.yml
```

