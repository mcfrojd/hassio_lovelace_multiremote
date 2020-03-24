# McFrojd's Home Assistant Lovelace Multi Remote
- 2020-03-24 Rewrite to use some other custom cards and integrations
- 2019-03-21 Updated to work with hassio 0.90, adb 0.3.0 and the new androidtv component

Lovelace example of my multi remote.

<p align="center">
<img src="https://raw.githubusercontent.com/mcfrojd/hassio_lovelace_multiremote/master/home_assistant_lovelace_remotes_2.gif" alt="Multiremote" width="300">
<img src="https://raw.githubusercontent.com/mcfrojd/hassio_lovelace_multiremote/master/home_assistant_lovelace_remotes_2.gif" alt="Multiremote" width="300">
</p>



### Lovelace Cards Used:

  - horizontal-stack | https://www.home-assistant.io/lovelace/horizontal-stack/

### HACS Plugins (Custom Cards) Used:

  - card-tools             | https://github.com/thomasloven/lovelace-card-tools
  - layout-card            | https://github.com/thomasloven/lovelace-layout-card
  - state-switch           | https://github.com/thomasloven/lovelace-state-switch
  - button-card            | https://github.com/custom-cards/button-card
  - decluttering card      | https://github.com/custom-cards/decluttering-card

### Home Assistant Community Add-on Used:

To controll Nvidia Shield TV
  - ADB - Android Debug Bridge | https://github.com/hassio-addons/addon-adb

Also installed on the dev machine (not needed for teh remote)
  - SSH & Web Terminal  | https://github.com/hassio-addons/addon-ssh
  - Samba Share         | https://github.com/home-assistant/hassio-addons/tree/master/samba
  - Visual Studio Code  | https://github.com/hassio-addons/addon-vscode

### HACS Integrations Used:

To controll TIVO Box
  - Virgin Tivo   | https://github.com/bertbert72/HomeAssistant_VirginTivo

### Home Assistant Integration Used:

To controll SONOS
  - SONOS          | https://www.home-assistant.io/components/sonos/

### Useful Forum Links:

  - https://community.home-assistant.io/t/community-hass-io-add-on-adb-android-debug-bridge/96375
  - https://community.home-assistant.io/t/compact-custom-header-custom-user-device-views/83716
  - https://community.home-assistant.io/t/control-tivo-box-over-telnet/12430
  - https://community.home-assistant.io/t/my-lovelace-plugins/70726
  - https://community.home-assistant.io/t/native-support-for-android-tv-android-devices/82792

### Se my public Gist of more types of "intents" for the Shield and its apps.
  - https://gist.github.com/mcfrojd/9e6875e1db5c089b1e3ddeb7dba0f304
