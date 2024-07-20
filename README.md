# Vyos Ansible
To run the configuration Ansible playbooks do the following.
```Ansible Commands
ansible-playbook playbooks/interfaces.yaml -i hosts.yaml -e @config/defaults.yaml  -vvv

```