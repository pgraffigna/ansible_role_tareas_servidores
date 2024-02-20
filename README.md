# ansible_role_tareas_servidores

Roles + playbooks para correr diversas tareas via Ansible en equipos con linux.

Testeado con qemu + ubuntu 20.04 + ansible 2.10

----

playbooks:
- handler_mail.yml
- usuarios_csv.yml

roles:
- docker
- fail2ban
- instalaciones (paquetes)
- mantenimiento (monitoreo de vms)
- notificaciones (via telegram)

