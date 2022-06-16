This repo contains code for setting up kubernetes cluster.<br><br>
Edit inventory file and add ip's of master and worker nodes. <br><br>
Then finally execute the ansible playbook main.yml and the kubernetes cluster will be setup in the given IP's.<br>
Command to execute ansible playbook: ansible-playbook main.yml