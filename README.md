# Bootstrap

Common plays for all nodes.

## Requirements

None

## Role Variables

- `default_group` and `default_group_gid` are the default group for all nodes
- `default_ssh_port` is the default port on which SSH will listen

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
         - bitsandbooks.bootstrap

## License

BSD

## Author Information

[Rob Dumas](https://robdumas.com/).
