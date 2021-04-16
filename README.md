
How to run a simple play that backs up the existing config from an Ubiquiti Edgeswitch:
ansible-playbook --limit dc2 -i hosts backupedgeswitch.yml

How to run the playbook against Edgeswitch:
ansible-playbook --limit dc2 -i hosts edgeswitch.yml
