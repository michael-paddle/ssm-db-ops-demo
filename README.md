# ssm-db-ops-demo
Demo scripts for operations on postgres databases with ansible aws_ssm lookup and module. 

Some examples:

    ansible-playbook -vvvv system-setup-playbook.yml

    ansible-playbook -vvvv key-rotate-playbook.yml -i simple.aws_ec2.yaml

    ansible-playbook -vvvv system-destroy-playbook.yml -i simple.aws_ec2.yaml

