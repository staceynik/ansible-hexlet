
# Ansible Playbooks

This repository contains a collection of Ansible playbooks for various tasks.

## Directory Structure

- `playbooks/`
  - `create_user.yml`: Creates users with specified shells.
  - `install_git.yml`: Installs Git on the target servers.
  - `setup_workspace.yml`: Sets up the workspace directory.
  - `main.yml`: Main playbook that includes other playbooks.

- `inventory.ini`: Inventory file containing the target hosts.


https://github.com/staceynik/ansible-hexlet/assets/48840427/62d77491-1829-45dd-b1d3-6c5cb7705965

# Tools install playbooks

## Description

This playbook sets up the development environment for users, including the installation and configuration of essential tools such as Git. It automates the process of provisioning and configuring Git on target machines, enabling users to effectively manage version control and collaborate on GitHub repositories.

## General Directory Structure

    inventory.ini: The inventory file for defining the target hosts.
    main.yml: The main playbook file.
    roles: The directory containing the roles used in the playbook.


https://github.com/staceynik/ansible-hexlet/assets/48840427/bad5ac72-493d-4ee4-89c9-a375ea57b47d



## Usage

To execute the playbooks, use the following command:


Make sure to update the inventory file (`inventory.ini`) with your target hosts.


## License

This project is licensed under the [MIT License](LICENSE).
