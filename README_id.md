<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Gemserv untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/gemserv)](https://ci-apps.yunohost.org/ci/apps/gemserv/)
![Status kerja](https://apps.yunohost.org/badge/state/gemserv)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/gemserv)

[![Pasang Gemserv dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gemserv)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Gemserv secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

A gemini server written in rust.

### Features

- Vhosts
- CGI
- User directories
- Reverse proxy
- Redirect
- SCGI
- Reload config on SIGHUP


**Versi terkirim:** 0.6.7~ynh1
## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://git.sr.ht/~int80h/gemserv/>
- Depot kode aplikasi hulu: <https://git.sr.ht/~int80h/gemserv>
- Gudang YunoHost: <https://apps.yunohost.org/app/gemserv>
- Laporkan bug: <https://github.com/YunoHost-Apps/gemserv_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
atau
sudo yunohost app upgrade gemserv -u https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
