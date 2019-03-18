# RaspberryPi Setup

Ansible recipes to install on a Raspberry Pi

## Dependencies

Make sure you have [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) 2.7+

```
$ ansible --version
ansible 2.7.9
```

Tested for Raspbian GNU/Linux 9 (stretch).

## Configuration

Create an entry on ~/.ssh/config pointing to your raspberry pi

```
Host pi
  HostName 192.168.1.66
  User pi
```

## Software

* Pyenv
* PHP
* Golang
* ngrok

## Execute

To apply all the roles, execute

```
$ ansible-playbook -i hosts main.yml
```