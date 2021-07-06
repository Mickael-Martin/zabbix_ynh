<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Zabbix for YunoHost

[![Integration level](https://dash.yunohost.org/integration/zabbix.svg)](https://dash.yunohost.org/appci/app/zabbix) ![](https://ci-apps.yunohost.org/ci/badges/zabbix.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/zabbix.maintain.svg)  
[![Install Zabbix with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zabbix)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Zabbix quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A monitoring tool for diverse IT components, including networks, servers, VMs and cloud services.

**Shipped version:** 4.4~ynh1

**Demo:** https://demo.example.com

## Disclaimers / important information

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * Configuration at install. SSO works. You can add your users in a group in Zabbix (for permissions/rights).
    * Only Debian - Stretch 64b supported actually.
    * Do not change the default admin user password. The user is disabled juste after the install but used to update templates.
    * The Zabbix server port is not opened by default for external monitoring (active agent).
    * A Yunohost template is imported and linked to the host "Zabbix-server" (127.0.0.1) for basic monitoring for YunoHost.
    * If you want more information about Yunohost in the template, please open an issue on git.

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentation and resources

* Official app website: https://example.com
* Official user documentation: https://www.zabbix.com/manuals
* Official admin documentation: https://yunohost.org/packaging_apps
* Upstream app code repository: https://framagit.org/Mickael-Martin/zabbix_ynh
* YunoHost documentation for this app: https://yunohost.org/app_zabbix
* Report a bug: https://github.com/YunoHost-Apps/zabbix_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/zabbix_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/zabbix_ynh/tree/testing --debug
or
sudo yunohost app upgrade zabbix -u https://github.com/YunoHost-Apps/zabbix_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps