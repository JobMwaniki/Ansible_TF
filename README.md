# AnsibleIP
Uses Ansible configuration playbooks that automates the provisioning and configuration of resources, as well as the deployment an application.
The project is set up in two stages
- ###### Stage 1: Ansible Instrumentation `/stage_1`
- ###### Stage 2: Ansible + Terraform instrumentation `/stage_2`

## Stage 1: Ansible Instrumentation
In this stage  the project uses an Ansible playbook, to automate Docker configuration on the target hosts, install the necessary images for the `client` and `backend` components, and run the containers. The playbook relies on the two roles,` docker-installation` and `docker-containers`, to perform these tasks.
## Stage 2: Ansible + Terraform instrumentation
In this stage  the project uses an Ansible playbook  automates the process of provisioning and configuration of resources and then install the necessary images for the `client` and `backend` components, and run the containers on the provisioned hosts.
