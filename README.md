# Ansible Role: go-repo.io Go Lang Repository

Installs go-repo.io's Go repo.

## Requirements

This role only is needed/runs on RHEL and its derivatives.

## Role Variables

See `defaults/main.yml`.

## Dependencies

None.

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-repo-go-repo-io.git
      name: nexcess.go-repo-io

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.go-repo-io

## License

MIT