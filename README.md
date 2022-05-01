<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Pagure for YunoHost

[![Integration level](https://dash.yunohost.org/integration/pagure.svg)](https://dash.yunohost.org/appci/app/pagure) ![](https://ci-apps.yunohost.org/ci/badges/pagure.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/pagure.maintain.svg)  
[![Install Pagure with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pagure)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Pagure quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A git-centered forge, python based using pygit2.

**Shipped version:** 5.13.3~ynh2

**Demo:** https://pagure.io

## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

* The admin you choose during the installation has been added to the PAGURE_ADMIN_USERS
* After installation, you must create an account with the same username

## Documentation and resources

* Official app website: https://pagure.io/pagure
* Official admin documentation: https://docs.pagure.org/pagure/
* Upstream app code repository: https://pagure.io/pagure
* YunoHost documentation for this app: https://yunohost.org/app_pagure
* Report a bug: https://github.com/YunoHost-Apps/pagure_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/pagure_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/pagure_ynh/tree/testing --debug
or
sudo yunohost app upgrade pagure -u https://github.com/YunoHost-Apps/pagure_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps