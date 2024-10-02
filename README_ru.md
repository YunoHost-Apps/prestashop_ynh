<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Prestashop для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/prestashop.svg)](https://ci-apps.yunohost.org/ci/apps/prestashop/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/prestashop.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/prestashop.maintain.svg)

[![Установите Prestashop с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prestashop)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Prestashop быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

PrestaShop is an Open Source e-commerce web application, committed to providing the best shopping cart experience for both merchants and customers. It is written in PHP, is highly customizable, supports all the major payment services, is translated in many languages and localized for many countries, has a fully responsive design (both front and back office), etc.

**Поставляемая версия:** 8.2.0~ynh3

**Демо-версия:** <https://demo.prestashop.com/#/en/front>

## Снимки экрана

![Снимок экрана Prestashop](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://prestashop.com>
- Официальная документация пользователя: <https://doc.prestashop.com/display/PS17/Guide+de+l'utilisateur>
- Репозиторий кода главной ветки приложения: <https://github.com/PrestaShop/PrestaShop>
- Магазин YunoHost: <https://apps.yunohost.org/app/prestashop>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/prestashop_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
или
sudo yunohost app upgrade prestashop -u https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
