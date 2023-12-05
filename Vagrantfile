Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/jammy64"
  config.disksize.size = "60GB"
  config.vm.hostname = "dev-stack-hello"
  # config.vm.network "public_network", bridge: "wlp2s0"
  config.vm.provider "virtualbox" do |v|
    v.memory = 8192
    v.cpus = 2
    v.name = "dev-stack-hello"
  end
  # config.vm.provision "shell", path: "dev_stack_setup.sh"

end
