Role Name
=========

ansible-vector-role

Requirements
------------

Ansible >= 2.10

Role Variables
--------------

Все переменные, которые могут быть переопределены, хранятся в файле [defaults/main.yml](defaults/main.yml), а также в таблице ниже.

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| vector_version | 0.41.1 | Верси vector |

Dependencies
------------

[git@github.com:AlexeySetevoi/ansible-clickhouse.git](git@github.com:AlexeySetevoi/ansible-clickhouse.git)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - vector-role

License
-------

BSD

Author Information
------------------

Mishanin Aleksandr

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
