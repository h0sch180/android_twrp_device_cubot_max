TWRP Device Tree for Cubot MAX 
===========
Unoffical Build for MT6753 TWRP 
------------------

the way to do:
```
- repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-6.0

- repo sync

- git clone https://github.com/h0sch180/android_twrp_device_cubot_max device/CUBOT/MAX

- . build/envsetup.sh

- lunch omni_MAX-eng

- make -j# recoveryimage [# : no. of cpu core]
```

