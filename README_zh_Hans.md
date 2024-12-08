<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Gemserv

[![集成程度](https://apps.yunohost.org/badge/integration/gemserv)](https://ci-apps.yunohost.org/ci/apps/gemserv/)
![工作状态](https://apps.yunohost.org/badge/state/gemserv)
![维护状态](https://apps.yunohost.org/badge/maintained/gemserv)

[![使用 YunoHost 安装 Gemserv](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gemserv)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Gemserv。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A gemini server written in rust.

### Features

- Vhosts
- CGI
- User directories
- Reverse proxy
- Redirect
- SCGI
- Reload config on SIGHUP


**分发版本：** 0.6.7~ynh1
## 文档与资源

- 官方应用网站： <https://github.com/calacuda/gemserv/>
- 上游应用代码库： <https://github.com/calacuda/gemserv/>
- YunoHost 商店： <https://apps.yunohost.org/app/gemserv>
- 报告 bug： <https://github.com/YunoHost-Apps/gemserv_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
或
sudo yunohost app upgrade gemserv -u https://github.com/YunoHost-Apps/gemserv_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
