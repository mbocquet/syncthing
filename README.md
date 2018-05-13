# syncthing

An Ansible role to install and configure Syncthing.

## Requirements

None.

## Role Variables

Many. See defaults/main.yml.

## Dependencies

None.

## Install this role as submodule of an existing GIT repository

`git submodule add https://github.com/mbocquet/syncthing.git roles/syncthing`

## Example Playbook

    - hosts: servers
      roles:
         - syncthing


    - hosts: servers
      roles:
         - { role: syncthing, x: 42 }

if any variables comes in the future for this role.

## License

GPLv3

## Author Information

<a href="http://www.sekoya.org" target="new">http://www.sekoya.org</a>
