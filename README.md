hello# hyperledgerlearning
Run following command
##centos:
ansible-playbook -i hosts -u centos preparedocker_centos.yml
##ubuntu
ansible-playbook -i hosts -u ubuntu preparedocker_ubuntu.yml
ansible-playbook -i hosts -u ubuntu preparepython_ubuntu.yml
ansible-playbook -i hosts -u ubuntu preparenodejs_ubuntu.yml
ansible-playbook -i hosts -u ubuntu preparetestenv_ubuntu.yml