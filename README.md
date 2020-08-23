# Ansible Task2

### Variables in ec2 Role:
* aws_instance_type
* ami_id
* aws_instance_tags
* subnet_id
* aws_region
* security_group_id

### Variables in webserver Role:
* package_name
* git_repo
* location


## Examples for ansible-playbook

* FILE_NAME.yml
```bash
hosts: HOSTS_NAME
roles:
 - roles: ROLE_NAME(Ex=> ec2,webserver)
```

## Command
* For running ansible-playbook:

```bash
ansbile-playbook PLAYBOOK.yml
```
* For running ansible-playbook using vault:
```bash
ansbile-playbook --ask-vault-pass PLAYBOOK.yml
```



# Detailed explanation 
[AnsibleTask2]()
