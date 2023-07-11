Role Name
=========

This role install Lighthouse


Role Variables
--------------
- `lighthouse_url` - ссылка на репозиторий;
- `lighthouse_dir` - рабочий каталог сервиса;
- `lighthouse_nginx_user` - пользователь под которым запущен nginx;
- `lighthouse_nginx_dir` - путь куда нужно положить nginx шаблон


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: lighthouse }

License
-------

MIT

Author Information
------------------

Yuri Kondratev
