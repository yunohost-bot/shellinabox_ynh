# Shell In A Box for YunoHost

[![Integration level](https://dash.yunohost.org/integration/shellinabox.svg)](https://dash.yunohost.org/appci/app/shellinabox) ![](https://ci-apps.yunohost.org/ci/badges/shellinabox.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/shellinabox.maintain.svg)  
[![Install Shell In A Box with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shellinabox)

> *This package allow you to install Shell In A Box quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

Shell In A Box implements a web server that can export arbitrary command line tools to a web based terminal emulator. This emulator is accessible to any JavaScript and CSS enabled web browser and does not require any additional browser plugins.

**Shipped version:** 2.21 (current Debian version)

## Screenshots

![](https://raw.githubusercontent.com/shellinabox/shellinabox/master/misc/preview.gif)

## Configuration

## Documentation

 * Official documentation: https://code.google.com/archive/p/shellinabox/wikis/shellinaboxd_man.wiki
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-users support

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/shellinabox.svg)](https://ci-apps.yunohost.org/ci/apps/shellinabox/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/shellinabox.svg)](https://ci-apps-arm.yunohost.org/ci/apps/shellinabox/)

## Limitations

## Additional information

## Links

 * Report a bug: https://github.com/YunoHost-Apps/shellinabox_ynh/issues
 * Shell In A Box website: https://github.com/shellinabox/shellinabox
 * Shell In A Box repository: https://github.com/shellinabox/shellinabox
 * YunoHost website: https://yunohost.org/

---

## Developers info

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/shellinabox_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/shellinabox_ynh/tree/testing --debug
or
sudo yunohost app upgrade shellinabox -u https://github.com/YunoHost-Apps/shellinabox_ynh/tree/testing --debug
```
