##Copy Files From S3##

#Usage#

This uses 2 environment variables, `S3_AWS_ACCESS_KEY_ID` and `S3_AWS_SECRET_ACCESS_KEY`.  Set those or use [Ansible Vault](http://docs.ansible.com/ansible/playbooks_vault.html)

This can also be used with remote hosts such as an EC2 instance without an IAM role.  This is useful if your upload speed is low.

`ansible-playbook -i localhost, playbook.yml`
