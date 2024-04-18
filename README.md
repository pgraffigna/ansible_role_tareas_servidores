# ansible_role_tareas_servidores

Roles + playbooks para correr diversas tareas via Ansible en equipos con linux.

Testeado con qemu + ubuntu 20.04 + ansible 2.15

---

### Descripción

La idea del proyecto es automatizar vía ansible varias tareas que realizo en servidores con linux, el repo cuenta con 6 roles:

1. actualizaciones
2. instalaciones
3. mantenimiento
4. notificaciones
5. docker
6. fail2ban

2 playbooks:

1. handler_mail
2. usuarios_csv

### Dependencias

* [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html)
* [Vagrant](https://developer.hashicorp.com/vagrant/install) (opcional)

### Uso

```
git clone https://github.com/pgraffigna/ansible_role_tareas_servidores.git
cd ansible_role_tareas_servidores
ansible-playbook main.yml
```

### Extras
* Archivo de configuración (Vagrantfile) para desplegar una VM descartable con ubuntu-22.04 con libvirt como hipervisor.

### Vagrant
```
vagrant up
vagrant ssh
```