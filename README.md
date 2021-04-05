# Grammalecte server for YunoHost

[![Integration level](https://dash.yunohost.org/integration/grammalecte.svg)](https://dash.yunohost.org/appci/app/grammalecte) ![](https://ci-apps.yunohost.org/ci/badges/grammalecte.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/grammalecte.maintain.svg)  
[![Install grammalecte with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=grammalecte)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Grammalecte quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Grammalecte is a spelling, grammar and typography checking service that supports French and Occitan. This package installs the server version, that provides an API for use by other programs (like LanguageTool).

**Shipped version:** 2.1.1

## Screenshots

![](https://grammalecte.net/grammalecte/img/screenshots/lo-correcteur1.png)

![](https://grammalecte.net/grammalecte/img/screenshots/lo-correcteur2.png)

## Configuration

The Grammalecte server can be configured by changing the command-line options of the `systemd` service `grammalecte.service`.

## Documentation

 * Official documentation: https://grammalecte.net/

#### Multi-user support

N/A

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/grammalecte.svg)](https://ci-apps.yunohost.org/ci/apps/grammalecte/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/grammalecte.svg)](https://ci-apps-arm.yunohost.org/ci/apps/grammalecte/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/grammalecte_ynh/issues
 * App website: https://grammalecte.net/
 * Upstream app repository: http://code.grammalecte.net:8080/
 * YunoHost website: https://yunohost.org/

---

## Developer info

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing --debug
or
sudo yunohost app upgrade grammalecte -u https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing --debug
```
