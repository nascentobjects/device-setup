# Nascent Device Setup

This will walk you through getting your new Nascent Main module setup with a new SSH password, device name, and get it connected to your home wireless network.

# Connecting to Your Device

* Start by inserting your main module, speaker module, and any other modules into your shape and plug it in.

* Wait 2 minutes for it to boot.

* Once booted, press the button on the back of your main module to enable wifi setup.  Once pressed, the button's light should blink on and off.

![Connect Image](https://github.com/nascentobjects/device-setup/raw/master/main_button_push.png)

The main module is now broadcasting as a wireless access point.  

* Connect your computer or mobile device to:

<table>
<tr><td>SSID:</td><td>Nascent Main</td></tr>
<tr><td>Password:</td><td>prototype</td></tr>
</table>

* Once successfully connected to the access point, open a web browser and navigate to:

http://192.168.42.1

* Use the device setup web portal to set your:
  1. SSH Password
  2. Device Name
  3. Home Wifi Network

* Once the device is connected to your wireless network, connect your computer or mobile phone back to your home wireless network.

You should now be able to ssh into the device with a command similar to:
```
ssh root@[DEVICE_NAME].local
```
Where [DEVICE_NAME] and the ssh password are the ones you specified.

