Vagrant.require_version ">= 2.0.0"

Vagrant.configure(2) do |config|

 config.vm.box = "ubuntu/bionic64"
 config.vm.network 'private_network', ip: '172.30.1.2'
 config.vm.provision "ansible_local" do |ansible|
   ansible.verbose = "v"
   ansible.playbook = "playbooks/setup.yml"
   ansible.galaxy_role_file = "roles/requirements.yml"
   ansible.galaxy_roles_path = "/home/vagrant/.ansible/roles"
   ansible.inventory_path = "inventories/vagrant/hosts"
   ansible.limit = "all"
 end

end
