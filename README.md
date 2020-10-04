# ansible_for_devops
ansible for devops engineer

## backup all_db

ansible-playbook -i inventory run.yml --tags backup

## backup one_by_one_db

ansible-playbook -i inventory run.yml --tags backup_one_by_one

## backup nova

ansible-playbook -i inventory run.yml --tags nova_backup

## backup keystone

ansible-playbook -i inventory run.yml --tags keystone_backup

## backup neutron

ansible-playbook -i inventory run.yml --tags neutron_backup

## backup cinder

ansible-playbook -i inventory run.yml --tags cinder_backup

## backup placement

ansible-playbook -i inventory run.yml --tags placement_backup

## backup rally

ansible-playbook -i inventory run.yml --tags rally_backup






## check ansible

ansible-playbook -i inventory run.yml --tags test


## change ip for backup db
###### step1i:
cd /mysql/
##### vim inventory
ip1

ip2

ip3
