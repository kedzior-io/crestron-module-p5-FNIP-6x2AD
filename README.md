# Crestron Module for P5 FNIP-6x2AD Ethernet Dimmer

This is Crestron module for ethernet dimmer from http://futurenow.hu

Product link: http://futurenow.hu/index.php/products/ethernet-modules/265-fnip-6x2ad

**Installation**:

1. Copy the content of /usrmacro to {Crestron directory}\Simpl\Usrmacro
2. Copy the content of /usrsplus to {Crestron directory}\Simpl\Usrsplus
3. Within Crestron Simpl import User Module: FNIP-6x2AD

**Signal description**:

- RX$ - String received from the device 
- TX$ - String sent to the device

- OutputToggle        - toggle for on/off
- OutputOn            - set channel to ON when high
- OutputOff           - set channel to OFF when high
- OutputAll           - trigger ON or OFF for all channels
- Dimming             - used with 1 button, when hold level goes up to 100 and back to 0
- DimmingUpOnHold     - when hold sets dim level up   
- DimmingDownOnHold   - when hold sets dim level down   
- DimmingByLevel 	  - setting brightness level by sending string (i.e "50")

- OutputFeedback      - goes high when channel level is greater then 0.
- OutputLevels        - reports channellevel as a string

Contact: klaatuveratanecto@gmail.com

![P5 FNIP-6x2AD Ethernet Dimmer](https://i.imgur.com/b2mHK2k.jpg)
