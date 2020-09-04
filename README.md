# Ansible Collection - medcelerate.arvados

Documentation for the collection.

## Developing

Install docker

usermod -a -G docker $USER

python3 -m venv venv/arvados-ansible

source venv/arvados-ansible/bin/activate

pip install ansible ansible-lint yamllint molecule docker 'molecule[docker]'
