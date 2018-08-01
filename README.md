# ansible-common
Ansible role for basic setup:

* repo
* packages
* users

## ansible tags

To skip package upgrade and/or basic packages use `--skip-tags` with:

* upgrade_packages: task that upgrades all installed packages to latest version
* basic_packages: set of basic packages that most people need

