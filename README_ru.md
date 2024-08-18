<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Gemserv для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/gemserv.svg)](https://ci-apps.yunohost.org/ci/apps/gemserv/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/gemserv.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/gemserv.maintain.svg)

[![Установите Gemserv с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gemserv)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Gemserv быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

A gemini server written in rust.

### Features

- Vhosts
- CGI
- User directories
- Reverse proxy
- Redirect
- SCGI
- Reload config on SIGHUP


**Поставляемая версия:** 0.6.6~ynh7
## Документация и ресурсы

- Официальный веб-сайт приложения: <https://git.sr.ht/~int80h/gemserv/>
- Репозиторий кода главной ветки приложения: <https://git.sr.ht/~int80h/gemserv>
- Магазин YunoHost: <https://apps.yunohost.org/app/gemserv>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/gemserv_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
или
sudo yunohost app upgrade gemserv -u https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
