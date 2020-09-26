# ansible_for_devops
ansible for devops engineer

## backup all_db

ansible-playbook -i inventory run.yml --tags backup

## backup one_by_one_db

ansible-playbook -i inventory run.yml --tags backup_one_by_one

## check ansible

ansible-playbook -i inventory run.yml --tags test


## change ip for backup db
###### step1i:
cd /mysql/
##### vim inventory
ip1

ip2

ip3
