<!--

---
lang: american
---
-->

[![Tweet this](http://img.shields.io/badge/%20-Tweet-00aced.svg)](https://twitter.com/intent/tweet?tw_p=tweetbutton&via=renard_0&url=https%3A%2F%2Fgithub.com%2Fcw-ansible%2Fcw-ansible&text=Manage%20all%20cw-ansible%20roles.)
[![Follow me on twitter](http://img.shields.io/badge/Twitter-Follow-00aced.svg)](https://twitter.com/intent/follow?region=follow_link&screen_name=renard_0&tw_p=followbutton)


# cw-ansible

Collection of [ansible](http://www.ansible.com/) roles.

## Configuration

All sensitive data and local configuration should be stored outside of the
orchestration directory. A typical layout could look like:

    .
    |-- README.md
    |-- private
    |-- playbooks
    |-- scripts
    `-- system-install

Configuration files:

- `ansible.cfg`: the main *Ansible* configuration file which is up to
  you. Have a look at the `ansible.cfg.example` file for configuration
  ideas.

- `private` This directory handle all you private data and configuration
  goes here. This is given by the `dir` option of the `custom` section from
  `ansible.cfg`




## Copyright

Author: Sébastien Gross `<seb•ɑƬ•chezwam•ɖɵʈ•org>` [@renard_0](https://twitter.com/renard_0)

License: WTFPL, grab your copy here: http://www.wtfpl.net
