# From
* ZBOSS is a registered trademark of DSR Corporation AKA Data Storage Research LLC.
* It was released dual license commercial and GPL 2.0 in 2012-2013.
* It implements the ZigBee Pro 2007 specification.
* It was best intented to target small micros like the 8051, as used on the Texas Instruments [CC2530](http://www.ti.com/product/cc2530)/[CC2531](http://www.ti.com/product/cc2531), and to be built with a comercial toolchain from ["IAR"](https://www.iar.com/).


# To
My ambition (December 2018) is
1. port the ZigBee 2007 codebase to be compiled by [SDCC](http://sdcc.sourceforge.net/) and to run on a TI CC2530, because that is the HW I have.
2. extend the code to talk [ZigBee Home Automation (ZBHA)](https://www.zigbee.org/zigbee-for-developers/applicationstandards/zigbeehomeautomation/) or even ZigBee 3.0
3. hack the clean compliant code to talk to third-party devices, such as Xiaomi wireless sensors.
4. make the result useful for tools such as [zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) to co-ordinate and mesh-network a ZigBee Intranet of Things, preferably with more-secure and less-internet.

This is not a small ambition and I do not know how much time I have to offer to this project. Let the game begin!
