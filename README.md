Role Base
=========

Example Playbook
----------------

- hosts: all
  remote_user: user
  become: true
  become_user: root
  become_method: sudo
  roles:
    - { role: role-base, user: "marcos" }

Author Information
------------------
Marcos Salcedo