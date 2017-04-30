# Ansible_Wordpress_Installation


Easy install of wordpress and signs in to a test-site.
------------------------------------------------------

Requirements
------------
1. Server ip address must be under [wordpress] in the 'hosts' file
2. IP address must also be pasted into group_vars file
3. SSH key file path must also be changed to your chosen path in group_vars file.
4. Cloud server must come with Python to utilise ansible
5. Simple Command is (to be executed in same folder): 
# ansible-playbook playbook.yml -i hosts -u root





