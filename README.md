# Streamhut for YunoHost

[![Integration level](https://dash.yunohost.org/integration/hedgedoc.svg)](https://dash.yunohost.org/appci/app/hedgedoc) ![](https://ci-apps.yunohost.org/ci/badges/hedgedoc.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/hedgedoc.maintain.svg)  
[![Install Streamhut with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=hedgedoc)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Streamhutquickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Streamhut allows you to stream (pipe) realtime data from your terminal stdout/stderr to a web xterm UI or even to another terminal. It also allow you to quickly share data and files between devices.

**Shipped version:** 0.0.8

## Screenshots

![](https://camo.githubusercontent.com/8fc50c755f3cedf509ba303470bd148b3f0c7bf5/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f6173736574732e73747265616d6875742e696f2f73747265616d6875745f64656d6f5f312e676966)

## Demo

* [Official demo](https://streamhut.io)

## Configuration

You can configure HedgeDoc by editing this file `/var/www/hedgedoc/config.json` using this the [documentation](https://github.com/hedgedoc/server/blob/master/docs/configuration.md)

## Documentation

 * Official documentation: 
 * YunoHost documentation: 

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **Yes**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/streamhut%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/streamhut/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/streamhut%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/streamhut/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/hedgedoc_ynh/issues
 https://streamhut.io/
 * Upstream app repository: https://github.com/streamhut/web
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/streamhut_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/streamhut_ynh/tree/testing --debug
or
sudo yunohost app upgrade streamhut -u https://github.com/YunoHost-Apps/streamhut_ynh/tree/testing --debug
```
