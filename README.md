Role Name
=========

This role was originally made to automate Fedora and Archlinux installations with all the tools I need for developing in different environments and using multiple programming languages. But like most Ansible automation content, its a living document. I wanted to show how Ansible automation can be used as a document for beginners. The tasks level can be confusing at first but, the `defaults/main.yml` has great information. 

In here I put every git repository that I would need and all the packages needed to build all the code to the programs I use. There's a large number of git repositories due to the fact that Archlinux or flavors (Manjaro) based on it used the same system packaging. A lot of software is not included and has to be made into packages to be installed with `pacman`.

Requirements
------------

Role Variables
--------------

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------
Adebisi Oyawale (aoyawale)
