<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Gemserv dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/gemserv)](https://ci-apps.yunohost.org/ci/apps/gemserv/)
![Status działania](https://apps.yunohost.org/badge/state/gemserv)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/gemserv)

[![Zainstaluj Gemserv z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gemserv)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Gemserv na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

A gemini server written in rust.

### Features

- Vhosts
- CGI
- User directories
- Reverse proxy
- Redirect
- SCGI
- Reload config on SIGHUP


**Dostarczona wersja:** 0.6.7~ynh1
## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://github.com/calacuda/gemserv/>
- Repozytorium z kodem źródłowym: <https://github.com/calacuda/gemserv/>
- Sklep YunoHost: <https://apps.yunohost.org/app/gemserv>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/gemserv_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
lub
sudo yunohost app upgrade gemserv -u https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
