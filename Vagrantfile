# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "bento/ubuntu-15.04"
  config.vm.network "private_network", ip:"192.168.40.40"
  config.vm.provision :ansible do |ansible|
    ansible.playbook = "passwordless.yml"
  end

end
