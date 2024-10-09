# Vyos Ansible
To run the configuration Ansible playbooks do the following.
```Ansible Commands
ansible-playbook playbooks/interfaces.yaml -i hosts.yaml -e @config/defaults.yaml  -vvv

```

## Known Issues
* On first run, the playbook will cause you to lose access when it
  configures the local zone. You need to manually add the changes.