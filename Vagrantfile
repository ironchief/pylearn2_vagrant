# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu-15-04"

  # config.vm.synced_folder "vm", "/home/vagrant"

  config.vm.provision :puppet do |puppet|
    puppet.module_path = "modules"
  end

end
