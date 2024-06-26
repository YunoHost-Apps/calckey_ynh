<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Calckey pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/calckey.svg)](https://dash.yunohost.org/appci/app/calckey) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/calckey.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/calckey.maintain.svg)

[![Installer Calckey avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=calckey)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Calckey rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Un fork grandement amélioré de Misskey avec une meilleure UI/UX, sécurité, fonctionnalités, et plus encore ! https://i.calckey.cloud/


    Calckey est basé sur Misskey, un puissant serveur de microblogging sur ActivityPub avec des fonctionnalités telles que des réactions emoji, une interface web personnalisable, des discussions riches, et bien plus encore !
    Calckey ajoute de nombreux changements de qualité de vie et des corrections de bogues pour les utilisateurs et les administrateurs d'instance.


**Version incluse :** 13.1.4.1~ynh1

**Démo :** <https://i.calckey.cloud/>

## Captures d’écran

![Capture d’écran de Calckey](./doc/screenshots/screenshot-calckey.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Calckey a été remplacée par Firefish, installez plutôt cette nouvelle application. Une procédure de migration est en cours de développement pour les instances existantes.

## Documentations et ressources

- Site officiel de l’app : <https://i.calckey.cloud/>
- Dépôt de code officiel de l’app : <https://codeberg.org/calckey/calckey>
- YunoHost Store : <https://apps.yunohost.org/app/calckey>
- Signaler un bug : <https://github.com/YunoHost-Apps/calckey_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/calckey_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/calckey_ynh/tree/testing --debug
ou
sudo yunohost app upgrade calckey -u https://github.com/YunoHost-Apps/calckey_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
