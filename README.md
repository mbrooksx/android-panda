android-panda
=============

This project ports the last TI OMAP4 release: (http://omappedia.org/wiki/4AJ.2.5P2_OMAP4_Jelly_Bean_Release_Notes) to the Pandaboard.
The intention is to then merge in the latest Android releases and have a stable k3.4 release with video and graphics acceleration.

Status:
* Boot of k3.4 is succesful (to Android home screen)
* HDMI output is functional
* SGX is functional
* Ducati is functional

Current Limitations:
* Audio is broken
* WiFi/BT Support is not enabled
* No support for Camera

Next Steps:
* ABE changes between k3.0 and k3.4 have broken audio
* WL127x has switched drivers, need to pull in latest. Additionally a BLE firmware is now available.
* Migrate this page from a series of patches to a manifest for creating an Android Repo
* Merge in KitKat





