# A complete guide to configuration management and orchestration with Ansible.


### Installing Ansible on Ubuntu

To configure the PPA on your machine and install Ansible run these commands:

```
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo apt-add-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible
```

*NB:*  SSH not installed on your Linux system? Add by updating packages and upgrading, then installing:

```
sudo apt update && sudo apt upgrade
sudo apt install openssh-client
```

Confirm your installation by running

```
ansible --version
ansible-playbook --version
ansible-galaxy --version

```

