<picture>
  <source media="(prefers-color-scheme: dark)" srcset="logo-primary-reversed.svg">
  <img alt="gridyard" src="logo-primary.svg" height="40">
</picture>

gridyard shows you how much electricity your home uses and feeds into the grid. A small reader sits on the infrared
port of your electricity or heat meter and sends its readings over your Wi-Fi.

| Repository | What it is | Status |
| --- | --- | --- |
| [home-assistant](https://github.com/Gridyard/home-assistant) | Home Assistant integration: add the reader, choose your meter, see your readings in the energy dashboard | In development |
| [firmware](https://github.com/Gridyard/firmware) | Signed firmware images for the reader; Home Assistant installs updates from here | No release yet |

## Local mode

Planned for the reader: without an account it talks only to devices on your own network, never to a gridyard
server. You set it up with the gridyard app, or with Home Assistant alone using the WPS button on your router.

[gridyard.de](https://gridyard.de) · [kontakt@gridyard.de](mailto:kontakt@gridyard.de)
