Role Name
=========

A roles to install and config Cerebro, Cerebro is an open source(MIT License) elasticsearch web admin tool built using Scala, Play Framework, AngularJS and Bootstrap .

Requirements
------------
- Java to run
- Working good with Elasticsearch v5.x

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

  # Define version
    cerebro_version: 0.8.3
  # Define directory execute
    cerebro_dir: /home/cerebro-{{cerebro_version}}/bin
  # Define url to download
    cerebro_url: https://github.com/lmenezes/cerebro/releases/download/v{{cerebro_version}}/cerebro-{{cerebro_version}}.zip


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

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

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
