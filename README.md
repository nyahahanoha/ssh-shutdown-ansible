# ssh-shutdown-ansible
When there are a lot of PCs, This code can test ssh command and shutdown command.

This method test shutdown to PCs.
ansible-playbook -i machines.cfg shutdown.yml

This method test ssh to PCs.
ansible-playbook -i machines.cfg echo.yml
