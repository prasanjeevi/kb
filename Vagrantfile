Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-18.04"

  config.vm.define "k8s-master" do |master|
    master.vm.network "private_network", ip: "192.168.50.10"
    master.vm.hostname = "k8s-master"
  end

end
