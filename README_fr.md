# PmWiki pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/pmwiki.svg)](https://dash.yunohost.org/appci/app/pmwiki) ![](https://ci-apps.yunohost.org/ci/badges/pmwiki.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/pmwiki.maintain.svg)  
[![Installer PmWiki avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pmwiki)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer PmWiki rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

PmWiki est un système de type wiki pour la création et l'entretien collectif de sites Internet. 

### Features

- Présentation personnalisée ;
- Contrôle d'accès ;
- Personnalisation et modules

**Version incluse :** 2.3.4~ynh1

**Démo :** https://demo.example.com

## Captures d'écran

![](./doc/screenshots/pmwiki.png)

## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentations et ressources

* Site officiel de l'app : https://www.pmwiki.org
* Documentation officielle utilisateur : https://www.pmwiki.org/wiki/PmWikiFr/PmWikiUsers
* Documentation officielle de l'admin : https://www.pmwiki.org/wiki/PmWikiFr/PmWikiFr
* Documentation YunoHost pour cette app : https://yunohost.org/app_pmwiki
* Signaler un bug : https://github.com/YunoHost-Apps/pmwiki_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/pmwiki_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/pmwiki_ynh/tree/testing --debug
ou
sudo yunohost app upgrade pmwiki -u https://github.com/YunoHost-Apps/pmwiki_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps