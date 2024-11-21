<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Gemserv voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/gemserv.svg)](https://ci-apps.yunohost.org/ci/apps/gemserv/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/gemserv.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/gemserv.maintain.svg)

[![Gemserv met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gemserv)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Gemserv snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

A gemini server written in rust.

### Features

- Vhosts
- CGI
- User directories
- Reverse proxy
- Redirect
- SCGI
- Reload config on SIGHUP


**Geleverde versie:** 0.6.7~ynh1
## Documentatie en bronnen

- Officiele website van de app: <https://git.sr.ht/~int80h/gemserv/>
- Upstream app codedepot: <https://git.sr.ht/~int80h/gemserv>
- YunoHost-store: <https://apps.yunohost.org/app/gemserv>
- Meld een bug: <https://github.com/YunoHost-Apps/gemserv_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
of
sudo yunohost app upgrade gemserv -u https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
