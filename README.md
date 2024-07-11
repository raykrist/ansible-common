# ansible-common

Ansible role for basic setup:

* repo
* packages
* users

## ansible variables

Change default behavior with these variables:

* upgrade_packages: false (default)
* install_common_packages: true (default)


## ansible tags

To skip package upgrade and/or basic packages at runtime use `--skip-tags` with:

* upgrade_packages: task that upgrades all installed packages to latest version
* common_packages: set of basic packages that most people need

## Requirements

``` yaml
collections:
  - name: ansible.posix
    version: 1.5.4
  - name: ansible.netcommon
    version: 5.1.2
  - name: community.general
    version: 8.2.0
```


