# Serveur Grammalecte pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/grammalecte.svg)](https://dash.yunohost.org/appci/app/grammalecte) ![](https://ci-apps.yunohost.org/ci/badges/grammalecte.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/grammalecte.maintain.svg)  
[![Installer grammalecte avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=grammalecte)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Grammalecte rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Grammalecte est un correctuer ortographique, grammatical, et typographique pour le Français et l'Occitan. Ce paquet installe la version serveur, qui fournit une API que d'autres programmes (comme LanguageTool par exemple) peuvent utilizer.

**Version incluse :** 2.1.1

## Captures d'écran

![](https://grammalecte.net/grammalecte/img/screenshots/lo-correcteur1.png)

![](https://grammalecte.net/grammalecte/img/screenshots/lo-correcteur2.png)

## Configuration

Le serveur Grammalecte peut etre configuré en changeant les options de ligne command du service `systemd` `grammalecte.service`.

## Documentation

 * Documentation officielle : https://grammalecte.net/

#### Support multi-utilisateur

S/O

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/grammalecte.svg)](https://ci-apps.yunohost.org/ci/apps/grammalecte/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/grammalecte.svg)](https://ci-apps-arm.yunohost.org/ci/apps/grammalecte/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/grammalecte_ynh/issues
 * Site de l'application : https://grammalecte.net/
 * Dépôt de l'application principale : http://code.grammalecte.net:8080/
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing --debug
ou
sudo yunohost app upgrade grammalecte -u https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing --debug
```
