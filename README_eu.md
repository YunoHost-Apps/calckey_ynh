<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Calckey YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/calckey.svg)](https://ci-apps.yunohost.org/ci/apps/calckey/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/calckey.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/calckey.maintain.svg)

[![Instalatu Calckey YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=calckey)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Calckey YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena


A greatly enhanced fork of Misskey with better UI/UX, security, features, and more! https://i.calckey.cloud/


    Calckey is based off of Misskey, a powerful microblogging server on ActivityPub with features such as emoji reactions, a customizable web UI, rich chatting, and much more!
    Calckey adds many quality of life changes and bug fixes for users and instance admins alike.
   


**Paketatutako bertsioa:** 13.1.4.1~ynh1

**Demoa:** <https://i.calckey.cloud/>

## Pantaila-argazkiak

![Calckey(r)en pantaila-argazkia](./doc/screenshots/screenshot-calckey.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Calckey has been replaced by Firefish, install that new app instead. A migration procedure is being developed for existing instances.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://i.calckey.cloud/>
- Jatorrizko aplikazioaren kode-gordailua: <https://codeberg.org/calckey/calckey>
- YunoHost Denda: <https://apps.yunohost.org/app/calckey>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/calckey_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/calckey_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/calckey_ynh/tree/testing --debug
edo
sudo yunohost app upgrade calckey -u https://github.com/YunoHost-Apps/calckey_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
