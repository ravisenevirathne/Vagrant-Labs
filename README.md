# Vagrant-Labs
Vagrant can be use to provision VMs with different configurations on virtual platforms. In this case we "VirtualBox" as the provider.

## Steps 

1. Install Vagrant 
    ```brew install --cask vagrant ```

2. Install VirtualBox 
    ```brew install --cask virtualbox  ```

3. Create a local folder on host computer and clone the repository
    ```git clone https://github.com/ravisenevirathne/Vagrant-Labs.git```

4. go to either lab1 or lab2 folder and execute the vagrant file
    ```vagrant up```

5. ssh into the powered on VM
    ```vagrant ssh vmname```

### Important Vagrant commands

- status of vagrant vm
    ```vagrant status```
- status of all vagrant VMs
    ```vagrant global-status```
- stop Vm
    ```vagrant halt```
- reload VM with updated config
    ```vagrant reload```
- reload VM using updated provisions (If the VM's are already existed)
    ```vagrant reload --provision```
    