## Deploy a LAMP stack on a new AWS virtual machine

### What is this?
This Ansible playbook deploys an EC2 instance on AWS, then deploys the LAMP stack to the provisioned virtual machine.

[This linuxschoolonline.com article](https://www.linuxschoolonline.com/use-ansible-to-build-and-manage-aws-ec2-instances/) helped with the creation of this Playbook.

### HOWTO
In order to run this Ansible playbook, you must do two things:
* Modify the `ansible.cfg` file by adding the path to your `.pem` file
* Add the variable values in `playbook.yml`

When you have done these things, you can launch the playbook by executing `ansible-playbook playbook.yml` in the terminal.

### License
This software is written by Noah Altunian (github.com/naltun), and is licensed under the terms of the
Apache version 2 license.

Love your Free/Libre, Open Source Software. For more information, please refer to [Wikipedia](https://en.wikipedia.org/wiki/Free_software_movement).
