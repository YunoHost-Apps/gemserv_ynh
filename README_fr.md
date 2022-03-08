# Gemserv pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/gemserv.svg)](https://dash.yunohost.org/appci/app/gemserv) ![](https://ci-apps.yunohost.org/ci/badges/gemserv.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/gemserv.maintain.svg)  
[![Installer Gemserv avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gemserv)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Gemserv rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

A gemini server written in rust.


**Version incluse :** 0.6.5~ynh2



## Avertissements / informations importantes

* Other infos that people should be aware of, such as:
    * Redirect TCP/1965 port to the server
    * To add a gemini capsule, create a /etc/gemserv/config.d/example.toml 

```
[[server]]
hostname = "youdomain.org"
dir = "/path/to/serv/"
key = "/etc/yunohost/certs/youdomain.org/key.pem"
cert = "/etc/yunohost/certs/youdomain.org/crt.pem"
# index is optional but defaults to index.gemini. The server will serve files
# ending in gemini or gmi.
index = "index.gmi"
# lang is optional
lang = "en"
# cgi is optional bool
cgi = true
# cgipath is optional and only checked if cgi is true. It restricts cgi to only
# this directory.
cgipath = "/path/to/cgi-bin/"
# scgi is optional
scgi = { "/scgi" = "localhost:4000" }
# cgienv is optional
cgienv = { "GIT_PROJECT_ROOT" = "/srv/git" }
# usrdir is optional. it'll look in /home/usr/public_gemini
usrdir = true
# proxy is optional
# path is what comes after the hostname e.g. example.com/path
proxy = { path = "localhost:1966" }
# proxy_all is optional
# It will send all requests to the specified server. It also supports streamming.
proxy_all = localhost:1967
# redirect is optional
redirect = { "/redirect" = "/", "/newdomain" = "gemini://example.net" }
```
## Documentations et ressources

* Dépôt de code officiel de l'app : https://git.sr.ht/~int80h/gemserv
* Documentation YunoHost pour cette app : https://yunohost.org/app_gemserv
* Signaler un bug : https://github.com/YunoHost-Apps/gemserv_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
ou
sudo yunohost app upgrade gemserv -u https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps