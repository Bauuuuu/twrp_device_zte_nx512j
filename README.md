# twrp_device_zte_nx512j
Compile twrp under omnirom environment


Get the omnirom minimal sources here 


repo init -u git://github.com/omnirom/android.git -b twrp-6.0


repo sync

clone this device tree into device/zte/nx512j folder of the source code directory

. build/envsetup.sh

lunch omni_nx512j-userdebug


make recoveryimage -j# 

(replace # with number of your processors)


