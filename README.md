# OS10 config push

Run the Ansible playbook to push the configs (jinja template) into your OS10 node</br>
The projecy config backup create jinja files automatically.

This example uses the dellos.dellos-copy-config role to push the configuration file into the device</br>
It creates a hosts file with the switch details and corresponding variables</br>
It writes a simple playbook that only references the dellos-copy-config role</br>
By including the role, you automatically get access to all of the tasks to push configuration file</br>

# How to use

ansible-playbook -i inventory pushconfig2.yml


#  NOTES

Install collections on your ansible control node </br>
ansible-galaxy install Dell-Networking.dellos-copy-config </br>

ref: https://github.com/Dell-Networking/ansible-role-dellos-copy-config 

ref: https://github.com/ansible-collections/dellemc.os10/tree/master/roles/os10_copy_config
