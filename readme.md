TWRP Device Tree for Cubot MAX
===========
Unoffical Build for MT6753 TWRP 
------------------

the way to do:
```
repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-5.1

repo sync -c

git clone https://github.com/h0sch180/android_twrp_device_cubot_max device/CUBOT/MAX

lunch omni_MAX-eng

mka recoveryimage
```

- test recovery twrp image (3.18.19)
- When you use newer kernel (3.18.79 or newer), you need to modify recovery.fstab