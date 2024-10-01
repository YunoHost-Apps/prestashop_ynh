<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Prestashop untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/prestashop.svg)](https://ci-apps.yunohost.org/ci/apps/prestashop/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/prestashop.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/prestashop.maintain.svg)

[![Pasang Prestashop dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prestashop)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Prestashop secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

PrestaShop is an Open Source e-commerce web application, committed to providing the best shopping cart experience for both merchants and customers. It is written in PHP, is highly customizable, supports all the major payment services, is translated in many languages and localized for many countries, has a fully responsive design (both front and back office), etc.

**Versi terkirim:** 8.2.0~ynh2

**Demo:** <https://demo.prestashop.com/#/en/front>

## Tangkapan Layar

![Tangkapan Layar pada Prestashop](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://prestashop.com>
- Dokumentasi pengguna resmi: <https://doc.prestashop.com/display/PS17/Guide+de+l'utilisateur>
- Depot kode aplikasi hulu: <https://github.com/PrestaShop/PrestaShop>
- Gudang YunoHost: <https://apps.yunohost.org/app/prestashop>
- Laporkan bug: <https://github.com/YunoHost-Apps/prestashop_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
atau
sudo yunohost app upgrade prestashop -u https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
