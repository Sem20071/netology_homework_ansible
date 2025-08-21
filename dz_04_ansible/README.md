# Домашнее задание к занятию 2 «Работа с Playbook»

## Основная часть
1. Допишите playbook: нужно сделать ещё один play, который устанавливает и настраивает LightHouse.
2. При создании tasks рекомендую использовать модули: get_url, template, yum, apt.
3. Tasks должны: скачать статику LightHouse, установить Nginx или любой другой веб-сервер, настроить его конфиг для открытия LightHouse, запустить веб-сервер.
4. Подготовьте свой inventory-файл prod.yml.
5. Запустите ansible-lint site.yml и исправьте ошибки, если они есть.
6. Попробуйте запустить playbook на этом окружении с флагом --check.
7. Запустите playbook на prod.yml окружении с флагом --diff. Убедитесь, что изменения на системе произведены.
8. Повторно запустите playbook с флагом --diff и убедитесь, что playbook идемпотентен.
9. Подготовьте README.md-файл по своему playbook. В нём должно быть описано: что делает playbook, какие у него есть параметры и теги.
10. Готовый playbook выложите в свой репозиторий, поставьте тег 08-ansible-03-yandex на фиксирующий коммит, в ответ предоставьте ссылку на него.

## Ответ:
### 1. Допишите playbook: нужно сделать ещё один play, который устанавливает и настраивает LightHouse.
![задание 1](https://github.com/Sem20071/netology_homework_ansible/blob/main/dz_03_ansible/images/ansible-03-01.png)
### 2. При создании tasks рекомендую использовать модули: get_url, template, yum, apt.
![задание 2](https://github.com/Sem20071/netology_homework_ansible/blob/main/dz_03_ansible/images/ansible-03-02.png)
### 4. Подготовьте свой inventory-файл prod.yml.
![задание 4](https://github.com/Sem20071/netology_homework_ansible/blob/main/dz_03_ansible/images/ansible-03-04.png)
### 5. Запустите ansible-lint site.yml и исправьте ошибки, если они есть.
![задание 5](https://github.com/Sem20071/netology_homework_ansible/blob/main/dz_03_ansible/images/ansible-03-05.png)
### 6. Попробуйте запустить playbook на этом окружении с флагом --check.
![задание 6](https://github.com/Sem20071/netology_homework_ansible/blob/main/dz_03_ansible/images/ansible-03-06.png)
### 7. Запустите playbook на prod.yml окружении с флагом --diff. Убедитесь, что изменения на системе произведены.
![задание 7](https://github.com/Sem20071/netology_homework_ansible/blob/main/dz_03_ansible/images/ansible-03-07.png)
### 8. Повторно запустите playbook с флагом --diff и убедитесь, что playbook идемпотентен.
![задание 8](https://github.com/Sem20071/netology_homework_ansible/blob/main/dz_03_ansible/images/ansible-03-08.png)
## ![задание 9](https://github.com/Sem20071/netology_homework_ansible/blob/main/dz_03_ansible/images/ansible-03-09.png)

## https://github.com/Sem20071/netology_homework_ansible/tree/main/dz_03_ansible
