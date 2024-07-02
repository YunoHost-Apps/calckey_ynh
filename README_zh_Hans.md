<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Calckey

[![集成程度](https://dash.yunohost.org/integration/calckey.svg)](https://ci-apps.yunohost.org/ci/apps/calckey/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/calckey.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/calckey.maintain.svg)

[![使用 YunoHost 安装 Calckey](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=calckey)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Calckey。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A greatly enhanced fork of Misskey with better UI/UX, security, features, and more! https://i.calckey.cloud/


    Calckey is based off of Misskey, a powerful microblogging server on ActivityPub with features such as emoji reactions, a customizable web UI, rich chatting, and much more!
    Calckey adds many quality of life changes and bug fixes for users and instance admins alike.
   


**分发版本：** 14.0.0rc3~ynh1

**演示：** <https://i.calckey.cloud/>

## 截图

![Calckey 的截图](./doc/screenshots/screenshot-calckey.png)

## :red_circle: 负面特征

- **Upstream not maintained**: Calckey has been replaced by Firefish, install that new app instead. A migration procedure is being developed for existing instances.

## 文档与资源

- 官方应用网站： <https://i.calckey.cloud/>
- 上游应用代码库： <https://codeberg.org/calckey/calckey>
- YunoHost 商店： <https://apps.yunohost.org/app/calckey>
- 报告 bug： <https://github.com/YunoHost-Apps/calckey_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/calckey_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/calckey_ynh/tree/testing --debug
或
sudo yunohost app upgrade calckey -u https://github.com/YunoHost-Apps/calckey_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
