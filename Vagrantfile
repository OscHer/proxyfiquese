# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
   config.vm.box              = "bento/ubuntu-24.04"
   config.vm.box_check_update = false
   config.vm.hostname         = "proxyfiquese"

   config.vm.provision :ansible_local do |ansible|
      # TODO-oscar: abstract path into a variable
      #ansible.playbook = "provision/ansible/playbook.yml"
   end
end
end
