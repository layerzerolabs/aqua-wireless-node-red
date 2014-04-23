aqua-wireless-node-red
======================

This code should be used together with aquaponics_jeenode.

It is intended to be run on a Raspberry Pi equipped with an RFM12b module. To interface with the RFM12b module, you will need to download the RFM12b_linux driver and its example code. How to use this is explained in our blog post: http://l0l.org.uk/2014/03/reading-multiple-sensors-rfm12b_linux-and-node-red/

It also uses gammu for text messaging, which will also need installing on the Pi. To send the text messages, a 3G dongle is required. Gammu is very easy to set up - its configuration process walks you through interfacing with the dongle.

If you don't want to use text messaging, just remove the relevant nodes.

This code also includes power switching via a hacked remote control. This will be explained in a forthcoming blog post at l0l.org.uk.


