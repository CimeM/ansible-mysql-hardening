
# Hardening mysql 
 
The role expects that mysql is already installed

## Task list
- Set the root password at the /defaults/main.yml

create a simple playbook:
'''
- name: Playbook
  hosts: servers
  become: yes
  roles:
    - mysql-hardening
'''

