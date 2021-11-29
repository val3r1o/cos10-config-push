# os10 config push

This example uses the dellos.dellos-copy-config role to push the configuration file into the device. It creates a hosts file with the switch details and corresponding variables. It writes a simple playbook that only references the dellos-copy-config role. By including the role, you automatically get access to all of the tasks to push configuration file.

# install collections on your ansible control node </br>
ansible-galaxy install Dell-Networking.dellos-copy-config </br>

ref: 
https://github.com/Dell-Networking/ansible-role-dellos-copy-config 

ref:
https://github.com/ansible-collections/dellemc.os10/tree/master/roles/os10_copy_config
