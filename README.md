# ansible-harderning-role
Run playbook for all host and user
```
ansible-playbook -i hosts main.yml
```
Run playbook for specific host group
```
ansible-playbook -i hosts main.yml -l web_server
```
