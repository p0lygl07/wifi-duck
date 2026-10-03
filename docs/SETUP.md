# WiFi Duck — Setup

## First-time setup

### 1. Power it
Plug the WiFi Duck into any USB port on a machine you own (it needs power, and it's also
the host it will type on).

### 2. Join its WiFi
The device creates its own WiFi access point. The **default** network name and password
ship with the Spacehuhn WiFiDuck firmware:

- **SSID:** `wifiduck`
- **Password:** `wifiduck`

> Change these in the web interface after first login — see the WiFiDuck docs
> (https://github.com/SpacehuhnTech/WiFiDuck). Don't leave the defaults if you'll use it around other people.

### 3. Open the interface
With your phone/laptop joined to that network, open a browser to the address in the
WiFiDuck docs (the device's AP gateway). You'll get a web UI to write, save, and run scripts.

### 4. Re-flashing firmware (only if needed)
Follow the upstream **WiFiDuck** flashing guide (https://github.com/SpacehuhnTech/WiFiDuck) — standard ESP32 web-flasher / esptool workflow.


---

Stuck? See [TROUBLESHOOTING.md](TROUBLESHOOTING.md). Use responsibly — [SAFETY.md](SAFETY.md).
