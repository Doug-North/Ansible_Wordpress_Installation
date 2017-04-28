# Ansible_Wordpress_Installation

Easy install of wordpress and signs in to a test-site.
1. Server  ip address must be under [wordpress] in the 'hosts' file
2. IP address must also be pasted into group_vars file
3. Cloud server must come with Python to utilise ansible
4. Simple Command is (to be executed in same folder): 

# ansible-playbook playbook.yml -i hosts -u root
