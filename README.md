## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) directories

[![Travis CI](http://img.shields.io/travis/debops/ansible-directories.svg?style=flat)](http://travis-ci.org/debops/ansible-directories) [![test-suite](http://img.shields.io/badge/test--suite-ansible--directories-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-directories/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.directories-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/1560)

This is a simple wrapper role around `file` Ansible module, which lets
you manage (create, modify or remove) directories using inventory
variables, including creation on multiple hosts at once.

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.directories

### Documentation

More information about `debops.directories` can be found in the
[official debops.directories documentation](http://docs.debops.org/en/latest/ansible/roles/debops.directories.html).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`directories` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
