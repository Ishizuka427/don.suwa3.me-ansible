# don.suwa3.me-ansible
![don suwa3 me-top](https://user-images.githubusercontent.com/45281231/64934735-c5123480-d887-11e9-9257-c0d55618db00.png)

## What is this?

Ansible for Configuration Management
- https://don.suwa3.me 
- A collection of Ansible playbooks

## How to use

### cron

```
ansible-playbook -i hosts cron.yml
```
### Switch to Maintenance mode

```
ansible-playbook -i hosts maintenance.yml
```
### Switch to Normal mode

```
ansible-playbook -i hosts normal.yml
```

## Creating the execution environment

```
python3 -m venv ./NAME
source ./NAME/bin/activate
pip install ansible
```

## Dependent Tools

- Python3
- Ansible
