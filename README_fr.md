<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Prestashop pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/prestashop.svg)](https://dash.yunohost.org/appci/app/prestashop) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/prestashop.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/prestashop.maintain.svg)

[![Installer Prestashop avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prestashop)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Prestashop rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

PrestaShop is an Open Source e-commerce web application, committed to providing the best shopping cart experience for both merchants and customers. It is written in PHP, is highly customizable, supports all the major payment services, is translated in many languages and localized for many countries, has a fully responsive design (both front and back office), etc.

**Version incluse :** 8.1.5~ynh1

**Démo :** <https://demo.prestashop.com/#/en/front>

## Captures d’écran

![Capture d’écran de Prestashop](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://prestashop.com>
- Documentation officielle utilisateur : <https://doc.prestashop.com/display/PS17/Guide+de+l'utilisateur>
- Dépôt de code officiel de l’app : <https://github.com/PrestaShop/PrestaShop>
- YunoHost Store : <https://apps.yunohost.org/app/prestashop>
- Signaler un bug : <https://github.com/YunoHost-Apps/prestashop_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
ou
sudo yunohost app upgrade prestashop -u https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
