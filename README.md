# Komga Home Assistant add-on repository

Hello! I have no idea what I'm doing but maybe this repository helps to get Komga started for you. 

I basically use a Raspberry PI5 with HAOS and mounted my external Harddrive, where all my manga are stored. I can simply drag all the manga files on my media share, which is being used by HA anyway. 
You may need to add this rule [here](https://gist.githubusercontent.com/eklex/c5fac345de5be9d9bc420510617c86b5/raw/d7010307ccee5c904c2a79f345680ffe6c6651bf/80-mount-usb-to-media-by-label.rules) via [udev](https://github.com/home-assistant/operating-system/blob/59b687f0dbb5c963c4a1b16bc574437a1aff99b3/Documentation/configuration.md), if you want that too.

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https://github.com/Nina-Syrina/HA-K/)

## Add-ons

This repository contains the following add-ons

### [Komga add-on](./Komga)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

_Example add-on to use as a blueprint for new add-ons._

<!--

Notes to developers after forking or using the github template feature:
- While developing comment out the 'image' key from 'example/config.yaml' to make the supervisor build the addon
  - Remember to put this back when pushing up your changes.
- When you merge to the 'main' branch of your repository a new build will be triggered.
  - Make sure you adjust the 'version' key in 'example/config.yaml' when you do that.
  - Make sure you update 'example/CHANGELOG.md' when you do that.
  - The first time this runs you might need to adjust the image configuration on github container registry to make it public
  - You may also need to adjust the github Actions configuration (Settings > Actions > General > Workflow > Read & Write)
- Adjust the 'image' key in 'example/config.yaml' so it points to your username instead of 'home-assistant'.
  - This is where the build images will be published to.
- Rename the example directory.
  - The 'slug' key in 'example/config.yaml' should match the directory name.
- Adjust all keys/url's that points to 'home-assistant' to now point to your user/fork.
- Share your repository on the forums https://community.home-assistant.io/c/projects/9
- Do awesome stuff!
 -->

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
