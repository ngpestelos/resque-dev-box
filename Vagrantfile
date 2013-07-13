# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ringtail64"
  config.vm.box_url = "https://dl.dropboxusercontent.com/u/6154794/Vagrant/ringtail64.box"

  config.vm.network :private_network, ip: "192.168.33.10"

  config.vm.synced_folder ".", "/vagrant", id: "vagrant-root", :nfs => true

end
