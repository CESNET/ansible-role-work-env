cesnet.work_env
=========

Role for setting Debian command-line environment.

* installs Czech locale and timezone
* installs vim, locate, htop, micro, zsh
* creates .bashrc which sets prompt and terminal title to show current working directory and hostname
* created .zshrc as recommended at https://wiki.debian.org/Zsh
* sets vim to remember position in each file
* sets htop to hide user threads 

Requirements
------------

--

Role Variables
--------------

--

Dependencies
------------

--

Example Playbook
----------------

```yaml
    - hosts: all
      roles:
         - cesnet.work_env
```

License
-------

Apache

Author Information
------------------

Martin Kuba, CESNET
