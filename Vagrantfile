Vagrant.configure(2) do |config|
  # A standard Ubuntu 12.04 LTS 32-bit box
  # For more boxes, you can look at https://atlas.hashicorp.com/boxes/search
  #config.vm.box = "ubuntu/trusty64"
  config.vm.box = "hashicorp/precise32"
  config.vm.provision "shell", path: "vag-setup.sh"
  # Create a private network, which allows host-only access to the machine
  # using a specific IP.
  config.vm.network "private_network", ip: "192.168.33.10"
end

