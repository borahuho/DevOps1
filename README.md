# DevOps1
```
With this vagrant, you will install one Ubuntu 18.04 machine.
This repository is intended for educational purpose only.
```

## Prerequisites
```
This setup is the first to try with my students.
Works on Windows 10

Software needed:
* Vagrant 2.2.6 or higher
* Virtualbox 5.0 or higher
* Git bash for Windows
```
## Installation
```
Install Virtualbox: https://www.virtualbox.org/wiki/Downloads
Install Git bash for Windows: https://gitforwindows.org/
Install Vagrant for Windows: https://www.vagrantup.com/downloads.html
```
## Run this Vagrant VM
Open Git Bash in Windows
```
cd Documents
mkdir vagrant && cd vagrant
git clone https://github.com/borahuho/DevOps1
cd DevOps1
vagrant up
vagrant ssh
```
## Network
Vagrant VM will be set up with 2 network adapters
```
Nat : DHCP
Localhost : 192.168.10.5
```
## Vagrant commands
Make a new VM with Vagrant
```
vagrant up
```
Stop and shutdown a VM
```
vagrant halt
```
Remove a VM
```
vagrant destroy
```
ssh in to the VM
```
vagrant ssh DevOps1
```

