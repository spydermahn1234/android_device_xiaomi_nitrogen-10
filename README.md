# android_device_xiaomi_nitrogen-10

Working :

ADB

Decryption userdata

Screen brightness settings

Correct screenshot color

MTP

..to compile

extract stock_kernel.tar.gz

. build/envsetup.sh

lunch omni_nitrogen-eng

export ALLOW_MISSING_DEPENDENCIES=true # Only if you use minimal twrp tree.

make -jX recoveryimage
