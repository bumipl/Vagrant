# Jak puszczac playbooka z tej ścieżki gdy #docker.ssh.insert_key = false

ansible-playbook --private-key=.vagrant/machines/docker-httpd/virtualbox/private_key -u vagrant -i .vagrant/provisioners/ansible/inventory/vagrant_ansible_inventory docker-httpd.yml
