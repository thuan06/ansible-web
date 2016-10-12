- Ansible auto deploy new vhost:
	+ Add site to Haproxy config
	+ Add config, code to web server 
- Modify hosts file for specific server
- Need change in create_vhost.yml/vars. 
- Run: ansible-playbook -i hosts create_vhost.yml
