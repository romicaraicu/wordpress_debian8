===========================================================================
### Ansible WP role

### Dependencies 
 - Debian 8
 - Ansible
 - Vagrant with VirtualBox

### Run vagrant:

	vagrant init debian/jessie64

### Clone git repo:

	git@github.com:romicaraicu/wordpress_debian8.git

### Check Vagrantfile and vagrant status:

	cd wordpress_debian8
	vagrant up

 - Access in browser: http://localhost:8080
  
===========================================================================
### Execute playbook with on VM:

### Clone git repo:

	git@github.com:romicaraicu/wordpress_debian8.git && cd wordpress_debian8

	ansible-playbook wp_playbook.yml -i hosts
	
 - Access in browser: http://YourVmIPaddress/
===========================================================================
