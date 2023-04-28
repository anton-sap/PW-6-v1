Database
=========

Роль позволяет устанавливать СУБД PostgreSQL на сервера под управлением операционной системы Debian/Ubuntu 

Role Variables
--------------
Переменная "postgresql_ver" позволяет выбрать версию пакета к установке. Принимаются значения от 10 до 15

Переменная "postgresql_data_dir" устанавливает директорию для дата-файлов

Dependencies
------------

Заисимостей не выявлено

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - database

License
-------

BSD

Author Information
------------------

anton-sap. DevOps студент
