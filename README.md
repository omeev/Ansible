To execute the ansible scripts run a commands like

1) Execute the script in test mode

   ansible-playbook -i <inventory_file> <playbook_file> --check

for eg:   ansible-playbook -i hostfile playbook_copy_file.yml --check

2) Execute the script to the server

   ansible-playbook -i <inventory_file> <playbook_file>

For eg:   ansible-playbook -i hostfile playbook_copy_file.yml
