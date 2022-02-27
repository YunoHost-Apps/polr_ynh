# Polr pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/polr.svg)](https://dash.yunohost.org/appci/app/polr) ![](https://ci-apps.yunohost.org/ci/badges/polr.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/polr.maintain.svg)  
[![Installer Polr avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=polr)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Polr rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble


**Version incluse :** 2.2.0

## Captures d'écran

![]()

## Démo

* [Démo officielle](https://demo.polr.me/)

## Configuration

Comment configurer cette application : via le panneau d'administration.

## Documentation

 * Documentation officielle : https://docs.polrproject.org/en/latest/
 * Documentation YunoHost : https://yunohost.org/#/app_polr_fr

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/polr%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/polr/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/polr%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/polr/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/polr_ynh/issues
 * Site de l'application : https://polrproject.org/
 * Dépôt de l'application principale : https://github.com/cydrobolt/polr
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/polr_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/polr_ynh/tree/testing --debug
or
sudo yunohost app upgrade polr -u https://github.com/YunoHost-Apps/polr_ynh/tree/testing --debug
```
