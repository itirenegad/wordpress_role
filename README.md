Role Name
=========
This worpress ansible role is used with a docker role. They allow to deploy wordpress with mysql database The deployment has been tested on Ubuntu and CentOS distributions.

Requirements
------------
Ubuntu and CentOS distributions.
itirenegad.docker_role

Role Variables
--------------

- Differents environmental variables were used for wordpress and mariadd.
- docker_role uses the suitable distribution and isntalls all requierements. 

Dependencies
------------

- itirenegad.docker_role

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts:
  - worker01 # Ubuntu
  - worker02 # CentOS
  roles:
     - role: itirenegad.docker_role
     - role: itirenegad.wordpress-role
     
     
License
-------
license (GPL-2.0-or-later, MIT, etc)

------------------

Learning from Sado Frazer
