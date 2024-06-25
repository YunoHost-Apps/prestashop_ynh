<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Prestashop

[![集成程度](https://dash.yunohost.org/integration/prestashop.svg)](https://dash.yunohost.org/appci/app/prestashop) ![工作状态](https://ci-apps.yunohost.org/ci/badges/prestashop.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/prestashop.maintain.svg)

[![使用 YunoHost 安装 Prestashop](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prestashop)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Prestashop。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

PrestaShop is an Open Source e-commerce web application, committed to providing the best shopping cart experience for both merchants and customers. It is written in PHP, is highly customizable, supports all the major payment services, is translated in many languages and localized for many countries, has a fully responsive design (both front and back office), etc.

**分发版本：** 8.1.7~ynh1

**演示：** <https://demo.prestashop.com/#/en/front>

## 截图

![Prestashop 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://prestashop.com>
- 官方用户文档： <https://doc.prestashop.com/display/PS17/Guide+de+l'utilisateur>
- 上游应用代码库： <https://github.com/PrestaShop/PrestaShop>
- YunoHost 商店： <https://apps.yunohost.org/app/prestashop>
- 报告 bug： <https://github.com/YunoHost-Apps/prestashop_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
或
sudo yunohost app upgrade prestashop -u https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
