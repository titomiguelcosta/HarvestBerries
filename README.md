# RaspberryPi Setup

Ansible recipes to install on Raspberry Pi

## Dependencies

Make sure you have [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) 2.7+

```
$ ansible --version
ansible 2.7.9
```

## Software

* Pyenv
* PHP
* ngrok

## Execute

To apply all the rolesm, execute

```
$ ansible-playbook -i hosts main.yml
```