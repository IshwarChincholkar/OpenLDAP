# OpenLDAP
Install openLDAP on docker container using Ansible playbook.
To run this project follow the steps:
1) Git clone
2) Change ip of host from host file and run the below command.
2) ansible-playbook -i hosts setup.yml --extra-vars "password=root cn_name=test dc_name1=companyName dc_name2=org"
