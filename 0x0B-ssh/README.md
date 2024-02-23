# SSH_0x0B-ssh

## About this project:

* In this project I learnt and practiced:
- what a sever is
- where severs usally live
- what is SSH
- How to create an SSH-RSA key pair
- How to connect to a remote host using SSH-RSA key pair
- The advantage of using #!/usr/bin/env bash instead of /bin/bash

## Tasks

* 0-use_a_private_key: Bash script that uses ssh to connect to my server ussing ~/.ssh/school.

* 1-create_ssh_key_pair: Bash script that creates an RSA key pair.

- Name of the created private key must be school
- Number of bits in the created key to be created 4096
- The created key must be protected by the passphrase betty

* 2-ssh_config: SSH configuration file configured to use the private key ~/.ssh/school and to refuse authentication using a password.
- The ssh config file is located at '/etc/ssh/ssh_config' ,
Here different options of config can be changed.
PasswordAuthentication no
IdentityFile ~/.ssh/school

* 100-puupet_ssh_config.pp: Puppet manifest that configures changes to our configuration file
Your SSH client configuration must be configured to use the private key ~/.ssh/school
Your SSH client configuration must be configured to refuse to authenticate using a password


