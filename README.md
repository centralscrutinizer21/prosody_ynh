<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->
⚠️ fork (work in progress) to install on Yunohost 12
and aiming at providing the best XMPP support possible!
Discussion on xmpp:yunohost-xmpp@muc.chapril.org?join ⚠️

# Prosody for YunoHost

[![Integration level](https://dash.yunohost.org/integration/prosody.svg)](https://dash.yunohost.org/appci/app/prosody) ![Working status](https://ci-apps.yunohost.org/ci/badges/prosody.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/prosody.maintain.svg)

[![Install Prosody with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prosody)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Prosody quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Prosody is a modern XMPP communication server. It aims to be easy to set up and configure, and efficient with system resources. Additionally, for developers it aims to be easy to extend and give a flexible system on which to rapidly develop added functionality, or prototype new protocols.


**Shipped version:** 0.12.4~ynh2
## Documentation and resources

* Official app website: <https://prosody.im/>
* Official admin documentation: <https://prosody.im/doc>
* Upstream app code repository: <https://hg.prosody.im/>
* YunoHost Store: <https://apps.yunohost.org/app/prosody>
* Report a bug: <https://github.com/YunoHost-Apps/prosody_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/prosody_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/prosody_ynh/tree/testing --debug
or
sudo yunohost app upgrade prosody -u https://github.com/YunoHost-Apps/prosody_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
