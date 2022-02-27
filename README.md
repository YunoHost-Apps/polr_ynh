# Polr for YunoHost

[![Integration level](https://dash.yunohost.org/integration/polr.svg)](https://dash.yunohost.org/appci/app/polr) ![](https://ci-apps.yunohost.org/ci/badges/polr.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/polr.maintain.svg)  
[![Install Polr with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=polr)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Polr quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview


**Shipped version:** 2.0.0

## Screenshots

![]()

## Demo

* [Official demo](https://demo.polr.me/)

## Configuration

How to configure this app: From an admin panel.

## Documentation

 * Official documentation: https://docs.polrproject.org/en/latest/
 * YunoHost documentation: https://yunohost.org/#/app_polr

## YunoHost specific features

#### Multi-user support

 * Are LDAP and HTTP auth supported? **No**
 * Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/polr%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/polr/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/polr%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/polr/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/polr_ynh/issues
 * App website: https://polrproject.org/
 * Upstream app repository: https://github.com/cydrobolt/polr
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/polr_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/polr_ynh/tree/testing --debug
or
sudo yunohost app upgrade polr -u https://github.com/YunoHost-Apps/polr_ynh/tree/testing --debug
```
