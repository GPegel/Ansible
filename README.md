# Ansible
Ansible

First: ssh-copy-id user@hostname.example.com

To run Ansible for all hosts: ansible-playbook site.yml -i hosts
To run Ansible for only www_servers: ansible-playbook site.yml -i hosts --limit www_servers

** Be sure to have the servers running (as configured in hosts)
