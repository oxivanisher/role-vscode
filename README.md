vscode
=======
[![Ansible Lint](https://github.com/oxivanisher/role-vscode/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-vscode/actions/workflows/ansible-lint.yml)

This role installs vscode.

Example Playbook
----------------
```yaml
- name: Install vscode
  hosts: client
  collections:
    - oxivanisher.linux_desktop
  roles:
    - role: oxivanisher.linux_desktop.vscode
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_desktop](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_desktop/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_desktop).
