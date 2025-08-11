How to create Vagrantfile  
vi Vagranfile  
Vagrant.configure("2") do |config  
  &nbsp;config.vm.box = "rockylinux/9"  
  config.vm.hostname = "rockylinux9"  
  config.vm.box_version = "6.0.0"  
end
