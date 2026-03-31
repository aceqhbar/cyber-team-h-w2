## Task 1

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




## Task 2

### 1. Показать директорию

```bash
pwd


### 2. Листинг файла


ls
ls -la


### 3. Создание директории


mkdir test_folder


### 4. Навигация в директорию 


cd test_folder


### 5. Создание Файла


touch file.txt


### 6. Изменение файла


nano file.txt


### 7. ПОказать содержимое файла


cat file.txt


### 8. Копировать файл 


cp file.txt copy.txt


### 9. Переименовать файл 


mv copy.txt new.txt


### 10. Удалить файл 


rm new.txt


### 11. Удалить директорию 


rm -r test_folder

