<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Webmin for YunoHost

[![Integration level](https://dash.yunohost.org/integration/webmin.svg)](https://dash.yunohost.org/appci/app/webmin) ![](https://ci-apps.yunohost.org/ci/badges/webmin.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/webmin.maintain.svg)  
[![Install Webmin with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=webmin)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Webmin quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Webmin is a web-based interface for system administration for Unix. Using any modern web browser, you can setup user accounts, Apache, DNS, file sharing and much more. Webmin removes the need to manually edit Unix configuration files like `/etc/passwd`, and lets you manage a system from the console or remotely.

**Shipped version:** 1.984~ynh1



## Screenshots

![](./doc/screenshots/screenshot1.gif)

## Disclaimers / important information

* This app has **root** access which can change core things in the system, thus **breaking the YunoHost**. Use it carefully and read the [documents](https://doxfer.webmin.com/Webmin/Main_Page) two times before changing values.
* Only **root** (system user) can connect 
* Webmin will **update itself** when system updates are run. So no need to **run upgrade script** once installed.
* Only **user** given permission at time of the installation can **access** the Webmin 

## Documentation and resources

* Official app website: http://www.webmin.com
* Upstream app code repository: https://github.com/webmin/webmin
* YunoHost documentation for this app: https://yunohost.org/app_webmin
* Report a bug: https://github.com/YunoHost-Apps/webmin_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/webmin_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
or
sudo yunohost app upgrade webmin -u https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps