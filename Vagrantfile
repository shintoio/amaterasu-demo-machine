# Vagrantfile for amaterasu dev station
Vagrant.configure(2) do |config|

  config.vm.box = "bento/centos-7.1"
  
  config.vm.define "node1" do |node1|
   
    node1.vm.network "private_network", ip: "192.168.33.11"
    node1.vm.hostname = "node1"
           
    node1.vm.provider "virtualbox" do |vb|
      vb.memory = "2048"
		  vb.cpus = 3
    end

    node1.vm.provision "shell", run: "always" do |s|
	    s.path = "provision.sh"
	    s.privileged = true
    end
 
  end

end
