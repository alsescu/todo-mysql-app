# todo-mysql-app

This repo contains 2 deployment files (an Ansible playbook and an inventory) and used to deploy the containerized todo-mysql-app to a target server. The deployment script also installs the packages that are specific to the deployment of this application.

To deploy the app simply git clone this repo, modify the server IP address or name server as well as the <port_on_the_target _host:port_on_the_container> from the <inventory.txt> file.

To deploy the app simply run:  ansible-playbook playbook-deploy-app.yml -i inventory.txt

For more details, please check the attached video: https://drive.google.com/file/d/1TJAjsYnBau8J3wMfNI2o150WObCwkC6z/view?usp=sharing
