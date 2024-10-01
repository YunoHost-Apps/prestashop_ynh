<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Prestashop YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/prestashop.svg)](https://ci-apps.yunohost.org/ci/apps/prestashop/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/prestashop.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/prestashop.maintain.svg)

[![Instalatu Prestashop YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prestashop)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Prestashop YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

PrestaShop is an Open Source e-commerce web application, committed to providing the best shopping cart experience for both merchants and customers. It is written in PHP, is highly customizable, supports all the major payment services, is translated in many languages and localized for many countries, has a fully responsive design (both front and back office), etc.

**Paketatutako bertsioa:** 8.2.0~ynh2

**Demoa:** <https://demo.prestashop.com/#/en/front>

## Pantaila-argazkiak

![Prestashop(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://prestashop.com>
- Erabiltzaileen dokumentazio ofiziala: <https://doc.prestashop.com/display/PS17/Guide+de+l'utilisateur>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/PrestaShop/PrestaShop>
- YunoHost Denda: <https://apps.yunohost.org/app/prestashop>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/prestashop_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
edo
sudo yunohost app upgrade prestashop -u https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
