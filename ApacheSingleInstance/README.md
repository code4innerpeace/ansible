# Project Title

This project contains my experiments with Ansible tool.

### Prerequisites

Install Ansible(Implemented on 2.4.2.0).\
Create 'hosts' file.\
===hosts file template===\
[all]\
1.2.3.4

### Execution

Create the 'hosts' file and the server ip to the 'hosts' file.
Execute below command.
```
ansible-playbook --private-key=Test.pem install_apache.yml -i hosts
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
