Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.provider "virtualbox" do |vb|
    vb.name = "ubuntu-vm"
  end
  config.vm.provision "shell",
    inline: "apt update && apt install -y vim curl telnet unzip wget net-tools htop nmap && useradd wellington"
end