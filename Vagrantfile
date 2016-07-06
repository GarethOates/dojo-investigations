# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
    
    config.vm.define "dojo" do |dojo|
    dojo.vm.hostname = "dojo"
    dojo.vm.box = "debian/jessie64"  
    dojo.vm.synced_folder "/Users/fronter/Documents/Dojo/Site", "/var/www/html"
    dojo.vm.network "private_network", ip: "192.168.33.60"
  end

end
