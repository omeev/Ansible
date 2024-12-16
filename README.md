To execute the ansible scripts run a commands like

1) Execute the script in test mode
   
   ansible-playbook -i hostfile playbook_copy_file.yml --check

4) Execute the script to the server

   ansible-playbook -i hostfile playbook_copy_file.yml
