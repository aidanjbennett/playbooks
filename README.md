# My Playbooks for Ansible

## To run a playbook run

```bash
ansible-playbook -i inventory -u aidan --ask-pass write-file.yaml
```

## To run a playbook with sudo
```bash
ansible-playbook -i inventory -u aidan --ask-pass --ask-become-pass setup-fail2ban.yaml
```
