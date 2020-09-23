# ansible_for_devops
ansible for devops engineer

## backup db

ansible-playbook -i inventory run.yml --tags backup

## check ansible

ansible-playbook -i inventory run.yml --tags test


## change ip for backup db
###### step1: cd /mysql/
##### vim inventory
ip1

ip2

ip3
