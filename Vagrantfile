# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"

  config.vm.network "public_network"

  # Get load shell script to BOX for provision configuration runs
  config.vm.provision "shell", path: "ShellProvisioning/JenkinsConfiguration.sh"

end
