# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-16.04"

  config.vm.provider "virtualbox" do |vb|
     vb.memory = 2048
     vb.name = "docker-internals"
     vb.cpus = 2
  end
end
