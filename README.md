
# Beginner Ansible Playbooks

This repository contains a collection of beginner-friendly Ansible playbooks for various tasks. These playbooks are designed to help new users get started with Ansible and understand its basic functionality.

## Prerequisites

Before running the playbooks, make sure you have the following installed:

- Ansible (version X.X or higher)
- A Linux/Unix environment (e.g., CentOS, Ubuntu)
- Basic knowledge of YAML and command-line usage
- Enter the configurations at /etc/ansible/hosts for remote servers where it will run.
### Installation

To install Ansible, you can use the package manager for your OS:

**On RHEL/CentOS:**
```bash
sudo yum install ansible wget -y
```

**On Ubuntu/Debian:**
```bash
sudo apt-get update
sudo apt-get install wget ansible -y
```

## Playbooks Overview

- **playbook1.yml**: A basic playbook that installs NGINX on a remote machine.
- **playbook2.yml**: A playbook that creates a user and sets file permissions.
- **playbook3.yml**: A playbook for setting up a basic LAMP stack.
- **playbook4.yml**: A simple playbook that manages firewall settings.

## How to Use

1. Clone the repository:
```bash
wget https://github.com/aryamanmaurya/BeginnerAnsiblePlaybooks.git
```

2. Navigate to the directory:
```bash
cd BeginnerAnsiblePlaybooks
```

3. Run a playbook:
```bash
ansible-playbook playbook1.yml
```

Make sure to adjust the inventory and variables based on your environment.

## Example

Here is an example of how to use the `playbook1.yml`:

```bash
ansible-playbook -i inventory playbook1.yml
```

This will install NGINX on the servers listed in your inventory file.

## Contributing

Feel free to fork this repository, make changes, and submit a pull request. Contributions are always welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
