Ansible ZSH Role
=========

This role installs zsh, oh-my-zsh, sensible default .zshrc and .zsh_aliases. Besides, it changes the shell of {{ansible_ssh_user}} to zsh. 

Requirements
------------

NONE

Role Variables
--------------

NONE

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: ChengLong.zsh }
```

License
-------

MIT

Author Information
------------------

Cheng Long
