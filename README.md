![Home Assistant Logo](https://www.home-assistant.io/images/blog/2023-09-ha10/home-assistant-logo-new.png)

# Window/Door Open Climate Control with Optional Sensors

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/michaelheichler/hass-blueprint-thermostat/hass-blueprint-thermostat.yaml)

## 🏠 Make Your Home Smarter and More Energy Efficient!

This **Home Assistant automation blueprint** helps you control your HVAC system efficiently by automatically turning it off when a window or door is open and turning it back on when everything is closed again. Additionally, the blueprint can send optional notifications when conditions like humidity, atmospheric pressure, or temperature exceed certain thresholds.

## 🚀 Features
- 🏰 **Automatic HVAC Control**: Turns off the heating/cooling system when any selected window or door is open, saving energy.
- 🔄 **Smart Restoration**: Restores the climate system once all windows or doors are closed.
- 📤 **Optional Notifications**: Notifies you about high humidity, low pressure, or specific outdoor temperatures.
- ⏳ **Configurable Timeout**: Set how long to wait before turning off the HVAC after a window or door is left open.
- 🔔 **Persistent Reminders**: If a window or door remains open for 15 minutes, you will be notified, and then every 5 minutes until the window or door is closed.

## 🛠️ Setup Instructions
1. **Select Your Devices**: Choose your climate control entity and the sensors for windows/doors.
2. **Optional Sensors**: Add temperature, humidity, and atmospheric pressure sensors if you'd like extra notifications.
3. **Notification Setup**: Pick the mobile device to receive notifications.
4. **Define Timeout**: Set the timeout duration before turning off the HVAC system.

## 🌟 Example Usage Scenarios
- 🚶 **Leaving the Door Open**: Automatically turns off the HVAC after a set period if the door is accidentally left open.
- 🌧 **Weather Notifications**: Get notified when outdoor humidity or pressure reaches specific values, allowing you to adjust your comfort settings.

## 📋 Blueprint Overview
- **Climate Entity**: Your heating/cooling system.
- **Window/Door Sensors**: Monitor if windows or doors are open.
- **Optional Sensors**: Notifications about humidity, temperature, and atmospheric pressure.
- **Notify Device**: Mobile device to receive notifications about actions and environmental updates.

## 📢 Example Notifications
- *"The living room window has been opened."*
- *"Humidity is above 60%. Consider closing the windows."*
- *"The HVAC system has been turned off after the timeout period."*
- *"The HVAC system is back to auto mode."*

This blueprint ensures your home stays energy efficient and comfortable with minimal effort.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/michaelheichler/hass-blueprint-thermostat/hass-blueprint-thermostat.yaml)

## 🏁 Get Started
1. Click the **Import Blueprint** button above.
2. Select the relevant entities in Home Assistant.
3. Relax while the blueprint manages your home's climate automatically!

