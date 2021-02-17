# Setup ansible user
ansible-playbook --limit "my_host" --user my_user --ask-become-pass servivi_cluster_ansible_setup.yml