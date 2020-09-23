# ansible_for_devops
ansible for devops engineer

## backup db

ansible-playbook -i inventory run.yml --tags backup

## check ansible

ansible-playbook -i inventory run.yml --tags test


## change ip for backup db
path cd /mysql/

172.16.105.96
172.16.105.97
172.16.105.157

