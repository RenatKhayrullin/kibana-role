Filebeat role
=========

Роль для установки Kibana на хостах с ОС: CentOS.

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| kibana_version | "7.16.2" | Параметр, который определяет какой версии kibana будет установлен |

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: kibana-role }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
