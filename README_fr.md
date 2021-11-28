# Prestashop pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/prestashop.svg)](https://dash.yunohost.org/appci/app/prestashop) ![](https://ci-apps.yunohost.org/ci/badges/prestashop.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/prestashop.maintain.svg)  
[![Installer Prestashop avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prestashop)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Prestashop rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

PrestaShop is an Open Source e-commerce web application, committed to providing the best shopping cart experience for both merchants and customers. It is written in PHP, is highly customizable, supports all the major payment services, is translated in many languages and localized for many countries, has a fully responsive design (both front and back office), etc.

**Version incluse :** 1.7.8.1~ynh1

**Démo :** https://demo.prestashop.com/#/en/front

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

## Configuration

1. The app will require to complete the registration process after the instllation is complete by **visiting the domain** on  which Prestashop is installed.
1. The MySQL database credentials will be sent to the **admin mail**. Fill these details while doing the registration process.

There is a documentation page dedicated to the post-installation process: http://doc.prestashop.com/display/PS17/Installing+PrestaShop#InstallingPrestaShop-Completingtheinstallation
## Documentations et ressources

* Site officiel de l'app : https://prestashop.com
* Dépôt de code officiel de l'app : https://github.com/PrestaShop/PrestaShop
* Documentation YunoHost pour cette app : https://yunohost.org/app_prestashop
* Signaler un bug : https://github.com/YunoHost-Apps/prestashop_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
ou
sudo yunohost app upgrade prestashop -u https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps