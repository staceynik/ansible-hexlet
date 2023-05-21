
# Ansible Playbooks

This repository contains a collection of Ansible playbooks for various tasks.

## Directory Structure

- `playbooks/`
  - `create_user.yml`: Creates users with specified shells.
  - `install_git.yml`: Installs Git on the target servers.
  - `setup_workspace.yml`: Sets up the workspace directory.
  - `main.yml`: Main playbook that includes other playbooks.

- `inventory.ini`: Inventory file containing the target hosts.

## Playbooks

### create_user.yml

This playbook creates users on the target servers. It takes input parameters for user names and shells and ensures that the specified users are present.

### install_git.yml

This playbook installs Git on the target servers using the appropriate package manager (apt, yum, etc.). It ensures that Git is installed and available for use.

### setup_workspace.yml

This playbook sets up the workspace directory on the target servers. It creates the directory and sets the appropriate permissions for the specified user.

### main.yml

The main playbook that includes other playbooks. It orchestrates the execution of the individual playbooks and ensures that the necessary tasks are performed in the desired order.



https://github.com/staceynik/ansible-hexlet/assets/48840427/62d77491-1829-45dd-b1d3-6c5cb7705965

# Tools install playbooks

## Description

This playbook sets up the development environment for users, including the installation and configuration of essential tools such as Git. It automates the process of provisioning and configuring Git on target machines, enabling users to effectively manage version control and collaborate on GitHub repositories.


## Usage

To execute the playbooks, use the following command:


Make sure to update the inventory file (`inventory.ini`) with your target hosts.


## License

This project is licensed under the [MIT License](LICENSE).
