# Configuring Ansible

## Configuration file

Certain settings in Ansible are adjustable via a configuration file(ansible.cfg). The stock configuration should be sufficient for most users, but there may be reasons you would want to change them.

### Getting the latest configuration

If installing Ansible from a package manager, the lastest `ansible.cfg` file should be present in `/etc/ansible`.

### Environmental configuration

Ansible also allows configuration of settings using environment variables. If these environment variables are set, they will override any setting loaded from the configuration file([list](https://docs.ansible.com/ansible/latest/reference_appendices/config.html#ansible-configuration-settings)).

### Command line option

Not all configuration options are present in the command line, just the ones deemed most useful or common. Settings in teh command line will override those passed through the configuration file and the environment([list](https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html#ansible-playbook)).
