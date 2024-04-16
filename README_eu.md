<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Grammalecte server YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/grammalecte.svg)](https://dash.yunohost.org/appci/app/grammalecte) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/grammalecte.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/grammalecte.maintain.svg)

[![Instalatu Grammalecte server YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=grammalecte)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Grammalecte server YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Grammalecte is a spelling, grammar and typography checking service that supports French and Occitan. This package installs the server version, that provides an API for use by other programs (like LanguageTool).

**Paketatutako bertsioa:** 2.1.1~ynh3

## Pantaila-argazkiak

![Grammalecte server(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://grammalecte.net>
- Jatorrizko aplikazioaren kode-gordailua: <http://grammalecte.net:8080>
- YunoHost Denda: <https://apps.yunohost.org/app/grammalecte>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/grammalecte_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing --debug
edo
sudo yunohost app upgrade grammalecte -u https://github.com/YunoHost-Apps/grammalecte_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
