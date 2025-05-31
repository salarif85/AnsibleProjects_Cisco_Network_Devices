# Route Interface Configuration - Ansible Project

This project provides Ansible playbooks and roles to automate the configuration of network routes and interfaces.

## Features

- Automated configuration of network interfaces
- Static route management
- Idempotent and repeatable deployments

## Requirements

- Ansible 2.9+
- Python 3.x
- Access to target network devices or servers

## Usage

1. Clone the repository:
    ```
    git clone <repository-url>
    cd route_Int_config
    ```

2. Edit the inventory file to match your environment.

3. Run the playbook:
    ```
    ansible-playbook -i inventory main.yml
    ```

## Directory Structure

- `main.yml` - Main playbook file
- `roles/` - Ansible roles for configuration
- `inventory` - Inventory of target hosts

## License

MIT License

## Author

Your Name