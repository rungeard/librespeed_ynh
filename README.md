<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# LibreSpeed for YunoHost

[![Integration level](https://dash.yunohost.org/integration/librespeed.svg)](https://dash.yunohost.org/appci/app/librespeed) ![Working status](https://ci-apps.yunohost.org/ci/badges/librespeed.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/librespeed.maintain.svg)

[![Install LibreSpeed with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=librespeed)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install LibreSpeed quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Very lightweight Speedtest.

**Shipped version:** 5.2.5~ynh1

**Demo:** https://librespeed.org

## Screenshots

![Screenshot of LibreSpeed](./doc/screenshots/librespeed_screenshot.gif)

## Disclaimers / important information

* Any known limitations, constrains or stuff not working :
    * Please visit [Troubleshooting, common problems, known limitations](https://github.com/librespeed/speedtest/wiki/Troubleshooting,-common-problems,-known-limitations) for more informations.
    * Important: ID obfuscation currently only works on 64-bit PHP! You might want to set `$redact_ip_addresses` to true in `results/telemetry_settings.php`, this way, all IP addresses will be removed from the telemetry for better privacy. This is disabled by default.

* Other infos that people should be aware of :
    * A basic front-end for visualizing and searching tests by ID is available in `domain.tld/results/stats.php`. A password is asked to you during installation steps to access this page. 

## Documentation and resources

* Official app website: <https://librespeed.org>
* Official user documentation: <https://github.com/librespeed/speedtest/wiki>
* Official admin documentation: <https://github.com/librespeed/speedtest/wiki>
* Upstream app code repository: <https://github.com/librespeed/speedtest>
* Report a bug: <https://github.com/YunoHost-Apps/librespeed_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/librespeed_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/librespeed_ynh/tree/testing --debug
or
sudo yunohost app upgrade librespeed -u https://github.com/YunoHost-Apps/librespeed_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
