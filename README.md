````markdown name=README.md
# door-unlock

**Unlock Door Automation Blueprint for Home Assistant**

This repository provides a Home Assistant automation blueprint to unlock your smart door when you arrive home and connect to your home WiFi.

## Features

- Unlocks the door when your device enters the home zone and connects to your WiFi SSID
- Optional notifications to your mobile devices
- Easy setup using Home Assistant Blueprints

## How to Use

1. **Import the Blueprint in Home Assistant:**
   - Go to *Settings → Automations & Scenes → Blueprints → Import Blueprint*
   - Paste the following raw file URL:
     ```
     https://github.com/GlerschNersch/door-unlock/raw/main/files/blueprint
     ```
   - Click *Preview* and then *Import Blueprint*

2. **Configure the Automation:**
   - Select your device tracker, home zone, lock entity, WiFi SSID sensor, and notification options.

## Blueprint File

- [Blueprint YAML](https://github.com/GlerschNersch/door-unlock/blob/main/files/blueprint)

## Credits

Created by Michael Leen  
For more home automation tutorials, visit [michaelsleen.com](https://www.michaelsleen.com/)

---

*Feel free to open issues or pull requests for enhancements!*
````
