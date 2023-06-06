<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Shell In A Box for YunoHost

[![Integration level](https://dash.yunohost.org/integration/shellinabox.svg)](https://dash.yunohost.org/appci/app/shellinabox) ![Working status](https://ci-apps.yunohost.org/ci/badges/shellinabox.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/shellinabox.maintain.svg)

[![Install Shell In A Box with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shellinabox)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Shell In A Box quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Shell In A Box implements a web server that can export arbitrary command line tools to a web based terminal emulator. This emulator is accessible to any JavaScript and CSS enabled web browser and does not require any additional browser plugins.


**Shipped version:** 2.21~ynh5

## Screenshots

![Screenshot of Shell In A Box](./doc/screenshots/screenshot.gif)

## Documentation and resources

* Official app website: <https://code.google.com/archive/p/shellinabox/>
* Official user documentation: <https://code.google.com/p/shellinabox/wiki/shellinaboxd_man>
* Official admin documentation: <https://github.com/shellinabox/shellinabox/wiki/shellinaboxd_man>
* Upstream app code repository: <https://github.com/shellinabox/shellinabox>
* YunoHost documentation for this app: <https://yunohost.org/app_shellinabox>
* Report a bug: <https://github.com/YunoHost-Apps/shellinabox_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/shellinabox_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/shellinabox_ynh/tree/testing --debug
or
sudo yunohost app upgrade shellinabox -u https://github.com/YunoHost-Apps/shellinabox_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
