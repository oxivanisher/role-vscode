vscode
=======
[![Ansible Lint](https://github.com/oxivanisher/role-vscode/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-vscode/actions/workflows/ansible-lint.yml)

This role installs vscode. It is now creating a deb822 file (again), since the `.deb` installer is checking for this and handling this correctly. This was discovered by unpacking the `.deb` and checking the `DEBIAN/postinst` script.

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
