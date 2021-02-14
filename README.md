# Nexus Ansible Roles

Installs Nexus 3.29.x on RedHat/CentOS linux system.

Nexus's default administrator account details are below
To change these credentials or version, change it on group_vars

    nexus_api_usr: 'admin'
    nexus_api_psw: 'admin123'
    nexus_version: '3.29.2-02'

## Requirements

To Do.

## Tree Structure

To Do.

## Role Variables

To Do.

## License

MIT

## Runing

```
git clone https://github.com/brpedromaia/nexus-ansible-roles.git
cd nexus-ansible-roles
sudo ansible-playbook --connection=local playbooks/setup.yml -t install
```

## References
- [Ansible Docs](https://docs.ansible.com/)
- [Jinja Template](https://jinja.palletsprojects.com/en/2.11.x/)
- [Sonartype Docs](https://help.sonatype.com/repomanager3/rest-and-integration-api)