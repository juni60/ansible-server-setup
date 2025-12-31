# Ansible Linux Server Configuration

This project demonstrates basic configuration management using Ansible.

## Project Overview

The playbook configures a Linux server with the following roles:

- **base**: Updates the system, installs utilities, and configures fail2ban
- **ssh**: Adds a public SSH key to the server
- **nginx**: Installs and starts nginx
- **app**: Uploads and extracts a static HTML website

## Usage

Run all roles:

```bash
ansible-playbook -i inventory.ini setup.yml
https://github.com/juni60/ansible-server-setup
