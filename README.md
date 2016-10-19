# storm-cluster-ansible
build a storm cluster on aws-ec2 with ansible

# How to run

At first, you should set your AWS token in environemnt variable  
```
export AWS_ACCESS_KEY_ID='AK123'
export AWS_SECRET_ACCESS_KEY='abc123'
```

For more details, you can refer to this link, http://docs.ansible.com/ansible/ec2_module.html.

set the path of pem file in ansible.cfg file
```sh
ansible-playbook main.yml
```

