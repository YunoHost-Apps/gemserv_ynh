<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Gemserv pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/gemserv.svg)](https://ci-apps.yunohost.org/ci/apps/gemserv/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/gemserv.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/gemserv.maintain.svg)

[![Installer Gemserv avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gemserv)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Gemserv rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Un serveur Gemini écrit en rust.

### Caractéristiques

- Hôtes virtuels
- CGI
- Dossiers utilisateurs
- Reverse proxy
- Redirection
- SCGI
- Rechargement de la configuration sur SIGHUP


**Version incluse :** 0.6.6~ynh8
## Documentations et ressources

- Site officiel de l’app : <https://git.sr.ht/~int80h/gemserv/>
- Dépôt de code officiel de l’app : <https://git.sr.ht/~int80h/gemserv>
- YunoHost Store : <https://apps.yunohost.org/app/gemserv>
- Signaler un bug : <https://github.com/YunoHost-Apps/gemserv_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
ou
sudo yunohost app upgrade gemserv -u https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
