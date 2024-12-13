<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Gemserv YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/gemserv)](https://ci-apps.yunohost.org/ci/apps/gemserv/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/gemserv)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/gemserv)

[![Instalatu Gemserv YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gemserv)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Gemserv YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

A gemini server written in rust.

### Features

- Vhosts
- CGI
- User directories
- Reverse proxy
- Redirect
- SCGI
- Reload config on SIGHUP


**Paketatutako bertsioa:** 0.6.7~ynh1
## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/calacuda/gemserv/>
- YunoHost Denda: <https://apps.yunohost.org/app/gemserv>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/gemserv_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
edo
sudo yunohost app upgrade gemserv -u https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
