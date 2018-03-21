# syncthing

An Ansible role to install and configure Syncthing.

## Requirements

None.

## Role Variables

Many. See defaults/main.yml.

## Dependencies

None.

## Install this roles as submodule of an existing GIT repository

`git submodule add https://github.com/mbocquet/syncthing.git roles/syncthing`

## Example Playbook

    - hosts: servers
      roles:
         - { role: syncthing }


    - hosts: servers
      roles:
         - { role: syncthing, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
