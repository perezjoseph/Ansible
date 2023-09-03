# Ansible
Ansible Scripts

This repository is a backup for the lab environment I used to practice Ansible. 

### Environment:
- Virtualbox
- Vagrant Ubuntu jammy
- Cygwin64 Terminal
- Ansible-cli

## Links
- Virtualbox 7.0.10 https://www.virtualbox.org/wiki/Downloads
- Vagrant 2.3.7 https://developer.hashicorp.com/vagrant/downloads?ajs_aid=46a68d14-9955-4b4d-b125-8f81fba22c9c&product_intent=vagrant
- Ubuntu Jammy Image https://app.vagrantup.com/ubuntu/boxes/jammy64
- Install ansible on Windows https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html

## Basic setup

Commands to get it up and running:

```shell
mkdir ansible && cd ansible
vagrant init ubuntu/jammy64
vagrant up
```
Or pull this repository:

```
git clone....
vagrant up
```
ssh to VM:

```shell
vagrant ssh
```
