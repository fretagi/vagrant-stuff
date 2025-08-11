Vagrant stuff

How to create a Vagrantfile for rocky linux

vi Vagrantfile
Vagrant.configure("2") do |config|
  config.vm.box = "rockylinux/9"
  config.vm.hostname = "rockylinux9"
  config.vm.box_version = "6.0.0"
end
