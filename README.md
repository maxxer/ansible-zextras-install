ansible-zextras-install
=========

A role for installing Zextras suite for Zimbra.

Role Variables
--------------

* `zextras_install_what`: What to install (core, zimlets, theme, all). Defaults to "all"
* `zextras_install_theme`: When installing "all" if include the theme. Defaults to "y"
* `zextras_workdir`: Temporary path for installer extraction. Defaults to `/tmp/zextras-installer`
* `zextras_install_timeout`: Task timeout. Defaults to 300

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
---
- hosts: g_zextras
  roles:
    - zextras_install
```

License
-------

See [`LICENSE`](LICENSE)

Author Information
------------------

https://www.yetopen.com | https://lorenzo.mile.si
