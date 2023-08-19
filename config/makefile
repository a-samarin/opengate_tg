setup_apps: nginx_up

install_apps:
	ansible-playbook --check playbooks/setup_webservers.yml -t install_apps -i inventory.ini

nginx_up:
	ansible-playbook --check playbooks/nginx.yml -i inventory.ini