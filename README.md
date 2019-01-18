# ansible docker

Provision EC2 Instances:
`ansible-playbook -i ec2.py ec2-provision.yml`

Termiante EC2 Instances
`ansible-playbook -i ec2.py ec2-terminate.yml`

Install Docker on provisioned EC2 Instances
`ansible-playbook -i ec2.py ec2-docker-install.yml`

_Currently only tested on a AWS `Ubuntu 18.04` EC2 instance!_
