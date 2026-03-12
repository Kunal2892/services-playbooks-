---
- name: Install MySQL 5.7
  hosts: servers
  become: yes

  tasks:

    - name: Update apt cache
      apt:
        update_cache: yes

    - name: Install MySQL 5.7
      apt:
        name: mysql-server-5.7
        state: present
