# ansible-role-elrepo

Role installs x2go server and client applications on RHEL and Ubuntu

## Requirements

None

## Role Variables

None

## Dependencies

* https://galaxy.ansible.com/goozbach/EPEL
(provides the x2go packages on RHEL family OS's)

## Example Playbook
'''
    - hosts: servers
      roles:
        - role: gabethecabbage.x2go
'''
