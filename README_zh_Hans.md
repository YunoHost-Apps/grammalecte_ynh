<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Grammalecte server

[![集成程度](https://apps.yunohost.org/badge/integration/grammalecte)](https://ci-apps.yunohost.org/ci/apps/grammalecte/)
![工作状态](https://apps.yunohost.org/badge/state/grammalecte)
![维护状态](https://apps.yunohost.org/badge/maintained/grammalecte)

[![使用 YunoHost 安装 Grammalecte server](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=grammalecte)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Grammalecte server。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Grammalecte is a spelling, grammar and typography checking service that supports French and Occitan. This package installs the server version, that provides an API for use by other programs (like LanguageTool).


**分发版本：** 2.1.1~ynh4

## 截图

![Grammalecte server 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://grammalecte.net>
- 上游应用代码库： <http://grammalecte.net:8080>
- YunoHost 商店： <https://apps.yunohost.org/app/grammalecte>
- 报告 bug： <https://github.com/YunoHost-Apps/grammalecte_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing --debug
或
sudo yunohost app upgrade grammalecte -u https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
