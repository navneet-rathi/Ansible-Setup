
# Ansible-Setup
This script will setup password less ssh from Ansible Controller to Nodes, Setup hostName,Setup Proxy.
* ansible -i host all -m ping -k
 * ansible -i host all -m setup -K -k
 * ansible-playbook -i host initial.yml -k -K
 
 it will ask for the password.
