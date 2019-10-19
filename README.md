Role Name
=========

This role deploys a minecraft server on Ubuntu linux.

Requirements
------------

The role will install some additional apps to help support running the mcserver, these include:
    - default-jre (java required for sever to run)
    - git
    - fail2ban
    - screen
    - vim

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

If you want to run the playbook against remote host(s), run the playbook below:


    - name: Deploy the minecraft server
      hosts: minecraft
    
      roles:
              - ansible-minecraft

If you want to run the playbook against the local host (where ansible is installed), run the playbook below.


    - name: Deploy the minecraft server
      hosts: localhost
      connection: local
    
      roles:
              - ansible-minecraft

License
-------

BSD

Author Information
------------------

Author: Russell Zachary Feeser

Contact:
    email: rzfeeser@gmail.com

Profession: Trainer and Consultant

Available for:
    - Ansible
    - Ansible Module Design with Python
    - Network Automation with Python and Ansible
    - Python for API and API Design
    - Python Basics
    - OpenStack
    - 5G
    - 4G LTE
    - IP Multimedia Subsystem
    - Session Initiation Protocol
