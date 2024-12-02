---
layout: blog
title: Getting started with Raspberry Pi
date: 2024-12-02T05:57:58.479Z
---
R﻿aspberry Pi is a mini computer (aka SBC) without the peripherals like keyboard, mouse, monitor etc. Older versions of Pi(Pi 2) do not even have Wi-Fi module. A SD card needs to be inserted into the Raspberry Pi and an Operating System( OS )should be loaded on to it. To load the OS onto the SD Card, insert the SD Card into a Windows/Mac machine, use Raspberry Pi Imager and select the OS to load onto it. 

![R﻿aspberry Pi Imager](/images/uploads/rpi_intro-e1583228263677.webp "R﻿aspberry Pi Imager")

**SSH:**

* S﻿SH allows you to remotely access the Raspberry Pi from another machine. This is called headless mode of accessing the Pi. If you have a monitor, you can connect to the Raspberry Pi via the HDMI cable.
* Y﻿ou can enable ssh by create a file called ssh with no contents in it on the root folder of the SD Card after OS is loaded. 

**W﻿i-Fi:**

C﻿heck this article on how to setup WiFi on the Pi without a monitor and keyboard

* https://www.raspberrypi-spy.co.uk/2017/04/manually-setting-up-pi-wifi-using-wpa_supplicant-conf/

**W﻿iFi Dongle:**

I﻿f you have older Raspberry Pi 2(like in my case), you may want to buy an Wi-Fi USB Adapter and plug it into the USB Slot of the PI. Refer to this instruction on how to setup one: https://www.electronicshub.org/setup-wifi-raspberry-pi-2-using-usb-dongle/