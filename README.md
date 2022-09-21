<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# SnappyMail for YunoHost

[![Integration level](https://dash.yunohost.org/integration/snappymail.svg)](https://dash.yunohost.org/appci/app/snappymail) ![Working status](https://ci-apps.yunohost.org/ci/badges/snappymail.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/snappymail.maintain.svg)  
[![Install SnappyMail with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=snappymail)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install SnappyMail quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Simple, modern, lightweight & fast web-based email client. The drastically upgraded & secured fork of RainLoop Webmail Community edition.


**Shipped version:** 2.18.1~ynh1


**Demo:** https://snappymail.eu/demo/
## Disclaimers / important information

:heavy_exclamation_mark: The password-file is created after first opening the admin UI!

:heavy_exclamation_mark: Be sure to immediately change the default password!

Open the admin UI `https://example.com/?admin` to configure your mail server settings. Login with user "admin" and password from the file `/var/www/snappymail/data/_data_/_default_/admin_password.txt`.

## Documentation and resources

* Official app website: <https://snappymail.eu/>
* Official admin documentation: <https://github.com/the-djmaze/snappymail/wiki>
* Upstream app code repository: <https://github.com/the-djmaze/snappymail>
* YunoHost documentation for this app: <https://yunohost.org/app_snappymail>
* Report a bug: <https://github.com/YunoHost-Apps/snappymail_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/snappymail_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/snappymail_ynh/tree/testing --debug
or
sudo yunohost app upgrade snappymail -u https://github.com/YunoHost-Apps/snappymail_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
