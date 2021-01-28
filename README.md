# AdGuard for YunoHost

[![Integration level](https://dash.yunohost.org/integration/adguard.svg)](https://dash.yunohost.org/appci/app/adguard) ![](https://ci-apps.yunohost.org/ci/badges/adguard.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/adguard.maintain.svg)  
[![Install adguard with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adguard)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install adguard quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Quick description of this app.

**Shipped version:** 0.104.3

## Screenshots

![](https://camo.githubusercontent.com/42b91eda808e2f68c98250679e29bcb0b0b4ef0364a4f67b6821982f4c87b1b3/68747470733a2f2f63646e2e616467756172642e636f6d2f7075626c69632f416467756172642f436f6d6d6f6e2f616467756172645f686f6d652e676966)

## Demo

* [Official demo](Link to a demo site for this app.)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

 * Are LDAP and HTTP auth supported?
 * Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/adguard%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/adguard/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/adguard%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/adguard/)

## Limitations

* Any known limitations.

## Additional information

 Fail to start ? try :

         $ systemctl status adguard
         $ apt install -y net-tools
         $ netstat -tlnp | grep 53




* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/adguard_ynh/issues
 * App website: https://adguard.com/fr/adguard-home/overview.html
 * Upstream app repository: https://github.com/AdguardTeam/AdGuardHome/
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/adguard_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/adguard_ynh/tree/testing --debug
or
sudo yunohost app upgrade adguard -u https://github.com/YunoHost-Apps/adguard_ynh/tree/testing --debug
```
