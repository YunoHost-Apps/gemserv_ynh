<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Gemserv para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/gemserv)](https://ci-apps.yunohost.org/ci/apps/gemserv/)
![Estado funcional](https://apps.yunohost.org/badge/state/gemserv)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/gemserv)

[![Instalar Gemserv con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gemserv)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarGemserv rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

A gemini server written in rust.

### Features

- Vhosts
- CGI
- User directories
- Reverse proxy
- Redirect
- SCGI
- Reload config on SIGHUP


**Versión actual:** 0.6.7~ynh1
## Documentaciones y recursos

- Sitio web oficial: <https://git.sr.ht/~int80h/gemserv/>
- Repositorio del código fuente oficial de la aplicación : <https://git.sr.ht/~int80h/gemserv>
- Catálogo YunoHost: <https://apps.yunohost.org/app/gemserv>
- Reportar un error: <https://github.com/YunoHost-Apps/gemserv_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
o
sudo yunohost app upgrade gemserv -u https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
