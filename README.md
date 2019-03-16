Ansible Role: tamay.composer
=========

This role installs [Composer](https://getcomposer.org/).  

Requirements
------------

PHP must be installed.

Role Variables
--------------

List of all variables, including default values.

    composer_install_path: /usr/local/bin

The path, where the composer binary will be installed into.

Dependencies
------------

None.

Example Playbook
----------------

    ---
    
    - hosts: all
    
      roles:
      - tamay.composer

License
-------

MIT

Author Information
------------------

tamay.mueller@gmail.com