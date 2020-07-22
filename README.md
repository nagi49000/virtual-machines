# virtual-machines

Collection of vagrant VMs to run for various purposes

## Requirements

Vagrant and Virtualbox installed on your machine

## Usage

cd into the virtual machine folder that has a 'Vagrantfile' in it. To launch the VM, at the command prompt run:

```
vagrant up --provision
```

If the VM has launched a jupyter server, it can be accessed on the local machine at

```
http://localhost:8888/tree
```