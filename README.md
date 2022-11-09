# Packer
## Prerequisites:

- AWS account - Follow official [link](https://portal.aws.amazon.com/billing/signup#/start/email) to create an account
- AWS CLI - Install and configure aws cli by following the official [documentation](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- Packer - Install Packer from the official [documentation](https://developer.hashicorp.com/packer/tutorials/docker-get-started/get-started-install-cli)
- Ansible - Install Ansible from the official [documentation](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

### Run below commands to generate a Golden AMI
- `packer init -upgrade packer.pkr.hcl`
- `packer validate packer.pkr.hcl`
- `packer build packer.pkr.hcl`
