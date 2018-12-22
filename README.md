# [DevOps практики и инструменты](https://otus.ru/lessons/devops-praktiki-i-instrumenty/)

Домашние задания по курсу DevOps практики и инструменты

[Mentor's code review 01](https://github.com/Otus-DevOps-2018-09/reomor_infra/pulls)

```
git submodule add  https://github.com/Otus-DevOps-2018-09/reomor_microservices.git micro
```
after git clone do
```
git submodule init
```

[git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)

---
### Infrastructure
#### Task 01
#### [No link]()
Работа с локальным и удаленным репозиториями, исправление комитов, решение конфликтов, работа с ветками и практика Code Review.

#### Task 02
#### [Travis CI & Slack integration](https://github.com/reomor/reomor_infra/tree/play-travis)
Настройка локального окружения и практика ChatOps.

#### Task 03
#### [Bastion Host GCP](https://github.com/reomor/reomor_infra/tree/cloud-bastion)
Запуск VM в GCP, управление правилами фаервола, настройка SSH подключения, настройка SSH подключения через Bastion Host, настройка VPN сервера и VPN-подключения.

#### Task 04
#### [Gcloud SDK](https://github.com/reomor/reomor_infra/tree/cloud-testapp)
Практика управления ресурсами GCP через gcloud.

#### Task 05
#### [Packer](https://github.com/reomor/reomor_infra/tree/packer-base)
Подготовка базового образа VM при помощи Packer.

#### Task 06
#### [Terraform-1](https://github.com/reomor/reomor_infra/tree/terraform-1)
Декларативное описание в виде кода инфраструктуры GCP, требуемой для запуска тестового приложения, при помощи Terraform.

#### Task 07
#### [Terraform-2](https://github.com/reomor/reomor_infra/tree/terraform-2)
Создание Terraform модулей для управления компонентами инфраструктуры.

#### Task 08
#### [Ansible-1](https://github.com/reomor/reomor_infra/tree/ansible-1)
Написание Ansible плейбуков на основе имеющихся bash скриптов.

#### Task 09
#### [Ansible-2](https://github.com/reomor/reomor_infra/tree/ansible-2)
Управление настройками хостов и деплой приложения при помощи Ansible.

#### Task 10
#### [Ansible-3](https://github.com/reomor/reomor_infra/tree/ansible-3)
Написание Ansible ролей для управления конфигурацией сервисов и настройками хостов.

#### Task 11
#### [Ansible-4](https://github.com/reomor/reomor_infra/tree/ansible-4)
Доработка имеющихся ролей локально с использование Vagrant.
