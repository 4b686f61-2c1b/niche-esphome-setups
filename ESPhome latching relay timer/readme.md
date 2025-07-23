# Features
- Latching relay
- Switch retains state even after power cycle
- Works offline (after RTC sync) and no reboot issues
- Nice user interface (4 pixel quality sorry)
- Scalable with shift register as I/O
- Low standby power in opposed to using contactors
    - Standard contactors still hold on at 25% the voltage but hitting it will retract the contacts. Because I do not like how these readable avaivable relays draw quite some current and hum loudly when enerigized, I have created this YAML configuration for ESPHome.
    - https://lcsc.com/product-detail/Magnetic-Latching-Relays_OMRON-G5RLU-1A-E-DC5_C1563148.html
          - For 5v relays, use a 1w resistor to match the resistance. 
    - https://lcsc.com/product-detail/Magnetic-Latching-Relays_QLRELAY-JMX-1125F-012-1HF_C22385003.html

## User interface
- Real time clock, includes day of the week, date and time formatted in 12H (can be changed)
- Indicates wheather if the [Home Assisstant API](https://esphome.io/components/api.html) is connected or not.
- If the [ESPhome Fallback AP](https://esphome.io/components/captive_portal.html#captive-portal) is on, it will be shown on the display
- Filled or outlined circles to indicate if the switch is on or off
- Live [WiFi reception](https://esphome.io/components/sensor/wifi_signal.html) updates, UI is capped at 99% due to my OCD
- (Pending) AC or Standby indicator when the load is active
- (Pending) Show current, voltage, wattage and total KWH passed through

# Coming Soon!
- PCB for this prototype
- ? ESP32-S3 ???
- When a power failure is detected, the relays will switch off
- Current Clamps
- Display current draw occasionally or via button cycle

# Access Point Demo
AP enabled as I went to touch some grass and the router was too far.

<img width="1337" height="644" alt="image" src="https://github.com/user-attachments/assets/68a0fb65-03e5-415f-b101-f08bbe3bb068" />

WiFi Menu samsung 💀

<img width="313" height="247" alt="image" src="https://github.com/user-attachments/assets/2bcbc2da-9c84-4197-92d9-d6ad8c2bf9cd" />

# Misc
Boot Logo 💀
<sup> Break the sterotype! We don't just porgram stuff, we design (safe and redundent) hardware.</sup>

<img width="620" height="441" alt="image" src="https://github.com/user-attachments/assets/7d4c0280-77e6-48af-8e3c-388c41677810" />

ESPhome Webserver
<img width="1689" height="955" alt="image" src="https://github.com/user-attachments/assets/2ae6c7bb-ccce-45d0-9e29-d6687c7dc8e4" />



