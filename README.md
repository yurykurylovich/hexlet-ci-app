# Example app for CI Hexlet course

Starting boilerplate of [Strapi](https://strapi.io/) application

## System requirements

* NodeJS >= 12 <= 16
* NPM >= 6.x
* Make

## Using

```sh
make setup
make start
```

## Run tests

```sh
make test
```

## Run linter

```sh
make lint
```

---

[![Hexlet Ltd. logo](https://raw.githubusercontent.com/Hexlet/assets/master/images/hexlet_logo128.png)](https://ru.hexlet.io/pages/about?utm_source=github&utm_medium=link&utm_campaign=hexlet-ci-app)

This repository is created and maintained by the team and the community of Hexlet, an educational project. [Read more about Hexlet (in Russian)](https://ru.hexlet.io/pages/about?utm_source=github&utm_medium=link&utm_campaign=hexlet-ci-app).


## Самостоятельная работа
В этой самостоятельной работе мы будем использовать репозиторий с готовым Strapi приложением.
1. Форкните и затем клонируйте репозиторий hexlet-ci-app

2. Создайте файл .github/workflows/main.yml в котором мы будем описывать наш главный воркфлоу

3. Опишите воркфлоу:

   - Он должен запускаться при каждом пуше в репозиторий

   - Используйте операционную систему ubuntu-latest

   - В шагах должны использоваться два экшена checkout@v2 и setup-node@v2

   - Используйте 16 версию Node.js

   - Выполните сетап проекта с помощью команды make setup

   - Запустите тесты командой make test

   - И наконец запустите линтер (анализатор на соответствие стандартам кодирования) командой make lint

4. Сделайте коммит и запуште изменения

5. Проверьте что воркфлоу успешно отработал
