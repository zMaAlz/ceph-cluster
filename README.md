# Ansible playbook для подготовки кластера Ceph
=========

Требуется
------------

Ansible 2.10 и новее 
ОС семейства Linux (Ubuntu, Debian, AstraLinux, CentOS, Fedora).

Манифесты
------------

install_first_mon.yml - Устанавливает cephadm на первую ноду, запускает mon.
add_new_host.yml - добавляет ноды в кластер Ceph.
install_osd.yml - Добалвяет на ноду OSD.

