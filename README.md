# ansible1

Ansible practice repository for the ITS24 program (Tartu Rakenduslik Kolledž).

## Contents

- Inventory and playbooks for managing Linux servers with Ansible

## Environment

- Control node: Ubuntu Server 24.04
- Ansible installed via apt

## Usage

```bash
ansible --version
ansible all -i inventory -m ping
```
