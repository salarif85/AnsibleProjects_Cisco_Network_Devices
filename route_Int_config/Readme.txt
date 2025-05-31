# Route Interface Configuration - Ansible Project

This project provides Ansible playbooks and roles to automate the configuration of network routes and interfaces.

## Features

- Automated configuration of network interfaces
- OSPF route management
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
    ansible-playbook -i inventory onfigure_routers.yml
    ```
4. Attached a screenshot of the Cisco Router network. 

## Directory Structure

- `configure_routers` - Main playbook file
- `ansible.cfg/` - Ansible  configuration
- `inventory` - Inventory of target hosts
- 'group_vars\cisco_routers' - Cisco routers configuration 

## License

MIT License

## Author

Sultan Al Arif