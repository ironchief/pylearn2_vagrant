#Pylearn2 in a box
This Vagrant package was designed to make Deep Neural Network research easily available.

##Setup
### Requirements
* Any OS (Linux, OSX, Windows)
* Vagrant
* Virtual Box

###Vagrant
Download and install Vagrant
http://www.vagrantup.com/

###Virtual Box
Download and install Virtual Box and VirtualBox Extension Pack
https://www.virtualbox.org/wiki/Downloads

###Download this repo
git clone etc

###Start the VM
    vagrant box add base http://files.vagrantup.com/lucid32.box
    vagrant init
    vagrant up
    vagrant ssh
