# ansible_role_tareas_servidores

Ansible rol + playbooks para correr diversas tareas via Ansible.

Testeado con qemu + ubuntu 20.04 + ansible_2.10

----

playbooks:
- handler_mail.yml
- parse_csv.yml

roles:
- docker
- instalaciones
- mantenimiento
- notificaciones