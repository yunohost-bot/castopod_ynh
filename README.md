<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Castopod for YunoHost

[![Integration level](https://dash.yunohost.org/integration/castopod.svg)](https://ci-apps.yunohost.org/ci/apps/castopod/) ![Working status](https://ci-apps.yunohost.org/ci/badges/castopod.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/castopod.maintain.svg)

[![Install Castopod with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=castopod)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Castopod quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Castopod is a free & open-source hosting platform made for podcasters who want engage and interact with their audience.
Castopod is easy to install and was built on top of CodeIgniter4, a powerful PHP framework with a very small footprint.


### Features

- Focused on data sovereignty: your content, audience, and analytics belong to you, and you only
- Podcasting 2.0 features: GUID, locked, transcripts, funding, chapters, location, persons, soundbites…
- Built-in social network, analytics, marketing tools
- Monetization
- Publish your episodes everywhere with RSS:
- Podcast import: move your existing podcast into Castopod
- Move your podcast out of Castopod
- Multi-tenant: host as many podcasts as you want
- Multi-user: add contributors and set roles

**Shipped version:** 1.12.2~ynh1

**Demo:** <https://podcast.podlibre.org/@podlibre_fr>

## Screenshots

![Screenshot of Castopod](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official app website: <https://castopod.org/>
- Official admin documentation: <https://docs.castopod.org/>
- Upstream app code repository: <https://code.castopod.org/adaures/castopod>
- YunoHost Store: <https://apps.yunohost.org/app/castopod>
- Report a bug: <https://github.com/YunoHost-Apps/castopod_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/castopod_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/castopod_ynh/tree/testing --debug
or
sudo yunohost app upgrade castopod -u https://github.com/YunoHost-Apps/castopod_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
