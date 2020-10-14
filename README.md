# Ansible Zabbix Agent

## Running Playbook

```bash
ansible-playbook -i inventory.yml playbook.yml
```

## Add More Hosts to `inventory.yml`

```
hosts:
  localhost:
    ansible_host: 127.0.0.1
```