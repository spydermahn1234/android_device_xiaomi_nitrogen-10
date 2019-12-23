# android_device_xiaomi_nitrogen-10

extract stock_kernel.tar.gz

to compile

. build/envsetup.sh

lunch omni_nitrogen-eng

export ALLOW_MISSING_DEPENDENCIES=true # Only if you use minimal twrp tree.

make -jX recoveryimage
