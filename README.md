# ansible-elk-demo
Ansible ELK Demo

## Prerequisites
* Install Hashicorp Vagrant
* Install VirtualBox

## Build Vagrant VMs
* Move to **vagrant** folder

~~~
cd vagrant
~~~

* Run vagrant to build the VirtualBox VMs

~~~
vagrant up
~~~

* Connect to elastic VMs in SSH to test the connection using the private ssh key from the repo

~~~
ssh vagrant@localhost -p 22222 -i .\id_rsa
ssh vagrant@localhost -p 22223 -i .\id_rsa
ssh vagrant@localhost -p 22224 -i .\id_rsa
~~~

