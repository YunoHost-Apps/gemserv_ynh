<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Gemserv per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/gemserv.svg)](https://dash.yunohost.org/appci/app/gemserv) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/gemserv.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/gemserv.maintain.svg)

[![Installa Gemserv con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gemserv)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Gemserv su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

A gemini server written in rust.

### Features

- Vhosts
- CGI
- User directories
- Reverse proxy
- Redirect
- SCGI
- Reload config on SIGHUP


**Versione pubblicata:** 0.6.6~ynh6
## Documentazione e risorse

- Sito web ufficiale dell’app: <https://git.sr.ht/~int80h/gemserv/>
- Repository upstream del codice dell’app: <https://git.sr.ht/~int80h/gemserv>
- Store di YunoHost: <https://apps.yunohost.org/app/gemserv>
- Segnala un problema: <https://github.com/YunoHost-Apps/gemserv_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
o
sudo yunohost app upgrade gemserv -u https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
