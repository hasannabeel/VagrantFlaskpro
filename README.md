flask-vagrant
=============

This is a vagrant box for working with flask.

### Requirements

- Vagrant > 1.5 (http://vagrantup.com) for creating the VM
- VirtualBox > 4.3.10 (http://www.virtualbox.org) for the VM container

### Getting Started

1. Make sure all requirements are satisfied.  Clone this project and `cd` into the project root
2. `vagrant up` to provision the virtualbox VM

### Starting the Server

1. `vagrant ssh` to go into the server
2. `cd /vagrant/hasan`
3. `python hello.py` to start the development server
  * Server: 192.168.76.76
4. Point your browser to http://192.168.76.76:5000

### Changing Parameters

- To change the IP address, modify `Vagrantfile` and change the `private_network` IP address
