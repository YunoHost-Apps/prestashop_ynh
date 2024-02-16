<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Prestashop for YunoHost

[![Integration level](https://dash.yunohost.org/integration/prestashop.svg)](https://dash.yunohost.org/appci/app/prestashop) ![Working status](https://ci-apps.yunohost.org/ci/badges/prestashop.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/prestashop.maintain.svg)

[![Install Prestashop with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prestashop)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Prestashop quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

PrestaShop is an Open Source e-commerce web application, committed to providing the best shopping cart experience for both merchants and customers. It is written in PHP, is highly customizable, supports all the major payment services, is translated in many languages and localized for many countries, has a fully responsive design (both front and back office), etc.

**Shipped version:** 8.1.3~ynh1

**Demo:** https://demo.prestashop.com/#/en/front

## Screenshots

![Screenshot of Prestashop](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://prestashop.com>
* Official user documentation: <https://doc.prestashop.com/display/PS17/Guide+de+l'utilisateur>
* Upstream app code repository: <https://github.com/PrestaShop/PrestaShop>
* YunoHost Store: <https://apps.yunohost.org/app/prestashop>
* Report a bug: <https://github.com/YunoHost-Apps/prestashop_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
or
sudo yunohost app upgrade prestashop -u https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>