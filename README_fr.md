<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Grammalecte server pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/grammalecte)](https://ci-apps.yunohost.org/ci/apps/grammalecte/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/grammalecte)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/grammalecte)

[![Installer Grammalecte server avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=grammalecte)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Grammalecte server rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Grammalecte is a spelling, grammar and typography checking service that supports French and Occitan. This package installs the server version, that provides an API for use by other programs (like LanguageTool).


**Version incluse :** 2.1.1~ynh4

## Captures d’écran

![Capture d’écran de Grammalecte server](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://grammalecte.net>
- Dépôt de code officiel de l’app : <http://grammalecte.net:8080>
- YunoHost Store : <https://apps.yunohost.org/app/grammalecte>
- Signaler un bug : <https://github.com/YunoHost-Apps/grammalecte_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing --debug
ou
sudo yunohost app upgrade grammalecte -u https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
