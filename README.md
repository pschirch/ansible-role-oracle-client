# Ansible Role: Oracle Client

Installs the Oracle Client. This role was created for bug finding regarding shell execution issue in Ansible > 1.6.10.

## Role Variables

See [defaults/main.yml](defaults/main.yml).
 
## Dependencies

None.

## Example Playbook

* create folder assets
* download [Oracle Client 11g Release 2 (11.2.0.1.0) for Linux x86-64](http://www.oracle.com/technetwork/database/enterprise-edition/downloads/112010-linx8664soft-100572.html) 
* save the package as oracle_client.zip in the assets folder

```
    - hosts: servers
      roles:
        - { role: pschirch.oracle-client }
```

## License

MIT / BSD

## Author Information

This role was created in 2015 by Patrick Schirch.
