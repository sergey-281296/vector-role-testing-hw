# Тестирование Ansible роли Vector

## Скриншоты выполнения

| Шаг | Описание | Скриншот |
|-----|----------|----------|
| 1 | Файлы роли в репозитории | ![01-role-files.png](screenshots/01-role-files.png) |
| 2 | Установка molecule и драйверов | ![02-molecule-install.png](screenshots/02-molecule-install.png) |
| 3 | Ошибка GitHub Actions | ![03-actions-failure.png](screenshots/03-actions-failure.png) |
| 4 | Ошибка Docker в WSL | ![04-docker-error.png](screenshots/04-docker-error.png) |

## Выполненные требования

- ✅ Установлен molecule и драйверы
- ✅ Сценарий default с дистрибутивами ubuntu:22.04 и oraclelinux:8
- ✅ Проверки assert в verify.yml
- ✅ Сценарий molecule/tox с драйвером podman
- ✅ tox.ini
- ✅ GitHub Actions workflow

## Репозиторий

https://github.com/sergey-281296/vector-role-testing-hw
