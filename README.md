 
This is an attempt at creating a touchscreen to control and display entities in Home Assistant using a Cheap Yellow Display (CYD).
It is a work in progress, being tweaked and modified when I come up with new ideas.
The backlight of the screen turns off after a time (default set to 45s) configurable in HomeAssistant.
Added is a function to help prevent "burn-in" of the screen, running for 30 mins four times every night.



# Add the following in your secrets.yaml file:
api_key
ota_password
wifi_ssid
wifi_password
ap_password
domain
