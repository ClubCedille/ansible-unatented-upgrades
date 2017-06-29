# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  # Every Vagrant development environment requires a box. You can search for
  # boxes at https://atlas.hashicorp.com/search.
  config.vm.box = "debian/jessie64"
  config.vm.box_version = "8.7.0"

  config.vm.provision :ansible do |ansible|
    ansible.playbook = "playbook.yml"
  end
end
