# Ansible Playbooks Collection

## Overview
This repository contains a collection of Ansible playbooks demonstrating various server management tasks. These playbooks are ideal for automating repetitive tasks in system administration.

## Playbooks
| Playbook                  | Description                                     |
|---------------------------|-------------------------------------------------|
| `install_app.yml`         | Installs applications on remote servers.        |
| `backup_files.yml`        | Creates backups of specified directories/files. |
| `manage_users.yml`        | Manages user creation, deletion, and permissions. |
| `cron_jobs.yml`           | Adds or updates cron jobs remotely.             |

## Usage
Clone the repository:
   ```bash
   git clone https://github.com/Suraj-Badrinarayanan-S/ansible-playbooks.git
   cd ansible-playbooks

# To run a playbook: 
ansible-playbook -i ~/.ansible/hosts “play-book-name”.yml

