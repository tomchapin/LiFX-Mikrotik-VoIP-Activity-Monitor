# lifx-mikrotik-phone-activity-monitor (v0.0.3)

1. Connects to your MikroTik router via SSH and uses the torch monitoring tool
   to identify how many VoIP phone calls currently active.

2. Updates the LiFX WiFi LED bulb's colors to reflect the hue, which is determined
   by the last part of the active phone's IP address. If more than one phone is in use,
   it will use an average of the combined colors

## Installation
1. Execute```bundle install```
2. Copy the 'config.example.yml' to 'config.yml' and set up the values in it

## Usage
Run the following command:
```
bundle exec ruby monitor_phone_router.rb
```
