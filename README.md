# Home Assistant Silicon Labs Multiprotocol (maintained fork)

## About

This repository is a narrowly-scoped fork that ships a single add-on:
**Silicon Labs Multiprotocol** (Zigbee + OpenThread on one SiLabs radio).
The official Home Assistant [`silabs-multiprotocol`](https://github.com/home-assistant/addons/tree/master/silabs-multiprotocol)
add-on is marked `stage: deprecated` upstream and no longer receives
updates. This fork tracks modern Simplicity SDK (v2024.12.1-0), CPC
daemon v4.6.1, Thread 1.4, and supports `armv7`, `aarch64`, and `amd64`.

For the other iHost-specific or upstream-covered add-ons that used to
live here, use the original sources:

| Add-on | Where to install from |
|---|---|
| eWeLink Smart Home, eWeLink-Remote Gateway, SONOFF Dongle Flasher, iHost Hardware Control, iHost Matter Bridge | [`github.com/iHost-Open-Source-Project/hassio-ihost-addon`](https://github.com/iHost-Open-Source-Project/hassio-ihost-addon) |
| SSH & Web Terminal, Node-RED, ESPHome | [Official Home Assistant Community Add-ons](https://github.com/hassio-addons) / upstream repos |
| Zigbee2MQTT | [`github.com/zigbee2mqtt/hassio-zigbee2mqtt`](https://github.com/zigbee2mqtt/hassio-zigbee2mqtt) |
| OpenThread Border Router | [`github.com/home-assistant/addons/openthread_border_router`](https://github.com/home-assistant/addons/tree/master/openthread_border_router) |
| Matter Server | [`github.com/home-assistant/addons/matter_server`](https://github.com/home-assistant/addons/tree/master/matter_server) |

## Installation
1. Go to the Add-on Store → Click the **More** button (⋮) in the upper-right corner → Select **Repositories**  
2. Paste the following URL:  
   [https://github.com/kije/hassio-ihost-addon](https://github.com/kije/hassio-ihost-addon)  
3. Or, simply click the button below to add it automatically:

[![Add Repository](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fkije%2Fhassio-ihost-addon)

## 🔄 Updating Repository

If you can only see part of the add-ons after adding this repository, it might be due to outdated local cache.  
To refresh:

1. Go to the Add-on Store  
2. Click the **More** button (⋮) in the upper-right corner  
3. Click **Check for updates**

This will force Home Assistant to reload the latest add-on list from all configured repositories.


## License

All add-ons in this repository are released under the [MIT License](./LICENSE).

---

## Maintainers

Maintained by the [iHost Open Source Project](https://github.com/iHost-Open-Source-Project).
