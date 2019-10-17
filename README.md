Role Name
=========

rbenv for serverspec 

Requirements
------------
https://galaxy.ansible.com/ysakkk/ansible_anyenv

Role Variables
--------------
version: "2.6.5"
local_dir: "/etc/ansible"


  version:   rbenv ruby version 
  local_dir: rbenv local dir 

Dependencies
------------
anyenv

Example Playbook
----------------

    - hosts: servers
      roles:
         - ysakkk.rbenv

