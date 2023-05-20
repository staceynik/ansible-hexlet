
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

## Usage

To execute the playbooks, use the following command:


Make sure to update the inventory file (`inventory.ini`) with your target hosts.


## License

This project is licensed under the [MIT License](LICENSE).



https://github.com/staceynik/ansible-hexlet/assets/48840427/62d77491-1829-45dd-b1d3-6c5cb7705965



