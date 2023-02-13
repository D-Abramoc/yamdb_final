# yamdb_final

# Учебный проект #

![Workflow for test, build and deploy](https://github.com/D-Abramoc/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)

Проект доступен по:
```
http://84.201.155.156/api/v1/
```
```
http://otzovik.sytes.net/api/v1/
```

## Описание ##

Цель проекта применить CICD при развертывании Django проекта

## Технологии ##

 - Python ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
 - Django  ![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
 - Docker
 - Git Action ![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

## Запуск проекта ##
- Установить docker и docker-compose
- Форкнуть репозиторий:
```
github.com/D-Abramoc/yamdb_final.git
```
- Перейти в директорию yamdb_final:
```
cd yamdb_final
```
- Создать и активировать виртуальное окружение
```
python3 -m venv venv
. venv/bin/activate
```

```
pip install -r api_yamdb/requirements.txt
```