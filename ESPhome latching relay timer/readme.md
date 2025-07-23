# Features
- Latching relay
- Switch retains state even after power cycle
- Works offline (after RTC sync) and no reboot issues
- Nice user interface (4 pixel quality sorry)
- Scalable with shift register as I/O
- Low standby power in opposed to using contactors
    - Standard contactors still hold on at 25% the voltage but hitting it will retract the contacts. Because I do not like how these readable avaivable relays draw quite some current and hum loudly when enerigized, I have created this YAML configuration for ESPHome.

# Coming Soon!
- PCB for this prototype
- ? ESP32-S3 ???
- When a power failure is detected, the relays will switch off
- Current Clamps
- Display current draw occasionally or via button cycle