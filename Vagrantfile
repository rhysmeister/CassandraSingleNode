Vagrant.configure("2") do |config|
  config.vm.box = "alonsodomin/ubuntu-trusty64-java8"

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end
end
