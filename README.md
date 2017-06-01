# Ansible Role: syslog-ng client installation and configuration

Installs syslog-ng and configures as client on Linux.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    syslog_ng_server_host: [specify you server here]

Specify the syslog-ng server host.

    syslog_ng_server_port: 1514

Specify the syslog-ng server host.

    syslog_ng_service: syslog-ng

Deafult syslog-ng service name.

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - syslog-ng-client

## License

MIT / BSD

## Author Information

This role was created in 2016 by Kálmán Szalai
