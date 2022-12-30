# Vagrant-Labs
Vagrant can be use to provision VMs with different configurations on virtual platforms. In this case we "VirtualBox" as the provider.

## Steps 

1. Install Vagrant 
    ``` shell
    brew install --cask vagrant

2. Install VirtualBox 
    ``` shell
    brew install --cask virtualbox

3. Create a local folder on host computer and clone the repository
    ``` shell
    git clone https://github.com/ravisenevirathne/Vagrant-Labs.git

4. go to either lab1 or lab2 folder and execute the vagrant file
    ``` shell
    vagrant up

5. ssh into the powered on VM
    ``` shell
    vagrant ssh vmname
6. once finish exit from vm and power down the vm
    ``` shell
    vagrant halt

### Important Vagrant commands

- status of vagrant vm
    ``` shell
    vagrant status
- status of all vagrant VMs
    ``` shell
    vagrant global-status
- stop Vm
    ``` shell
    vagrant halt
- reload VM with updated config
    ``` shell
    vagrant reload
- reload VM using updated provisions (If the VM's are already existed)
    ``` shell
    vagrant reload --provision
    