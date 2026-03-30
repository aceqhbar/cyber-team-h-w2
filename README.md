### 1. Определение текущего пользователя

```bash
whoami


### 2. Создание файла с настройками sudo


sudo visudo -f /etc/sudoers.d/nopasswd-lab


### 3. Добавление правила

kali2 ALL=(ALL) NOPASSWD: ALL


### 4. Сброс кеша sudo

sudo -k

### 5/ Проверка работы

sudo ls /root

### 6. Просмотр файла с настройками

sudo cat /etc/sudoers.d/nopasswd-lab

```bash

