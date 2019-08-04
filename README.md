# ansible-memcached

- Install Memcached Servers with Ansible.
- OS: CentOS 7

## Before Install
- Use DNS Server or update /etc/hosts for all servers.

### Install Memcached Server.
- Run the playbook.

```
ansible-playbook -i hosts memcached.yml
```
