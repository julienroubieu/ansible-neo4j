# Ansible role to install Neo4j Enterprise on top of Oracle Java 7

* Ansible: [http://www.ansible.com/home](http://www.ansible.com/home).

# Vagrant

This project is also integrated with Vagrant. You can use Vagrant to create a local VM and test this role.

To do this:

* Install Vagrant from [http://www.vagrantup.com](http://www.vagrantup.com/downloads.html)
* Run `vagrant up` to turn the VM on and automatically run the vagrant.yml playbook.
* To run it again, 2 solutions:
  * From vagrant: `vagrant provision`
  * From ansible directly: `ansible-playbook -s -i vagrant_host vagrant.yml -vv`