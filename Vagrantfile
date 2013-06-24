# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "precise64"

  config.vm.box_url = "http://files.vagrantup.com/precise64.box"

  # config.vm.synced_folder "vm", "/home/vagrant"

  config.vm.provision :puppet do |puppet|
    puppet.module_path = "modules"
  end

end
