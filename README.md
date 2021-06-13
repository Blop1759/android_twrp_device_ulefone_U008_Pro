Ulefone U008 Pro
================

The Ulefone U008 Pro (codenamed _"U008_Pro"_) is a flagship smartphone from Ulefone.

It was announced in 2016.

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | 1.3GHz Quad-Core MT6737M
GPU     | Mali-T720MP1
Memory  | 2GB RAM
Shipped Android Version | 6.0
Storage | 16GB
Battery | 3500 mAh
Display | 5" 1280 x 720 px
Rear Camera | 8MP (Samsung)
Front Camera | 5MP (Samsung)

![Ulefone U008 Pro](https://www.devicespecifications.com/images/model/ad9c4028/320/main.jpg "Ulefone U008 Pro in black")

This branch is for building TWRP (device tree for 7/7.1 at least)

### Thanks to:
 * CyanogenMod team
 * LineageOS team
 * OmniRom team
 * Deepflex
 * Team M.A.D
 * Decker
 * XDA forum

### To build: 
```
repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-7.1

repo sync

. build/envsetup.sh

lunch omni_U008_Pro-userdebug

make clean && make recoveryimage
```
