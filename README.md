## DaxConfig
 Replace default DaxConfig file with DaxConfig from different Xiaomi devices.
 
 Source : https://dumps.tadiphone.dev

 
## Requirement
 this is config file only, not module (install manually by replacing the file in directory).
   
    /vendor/etc/dolby/dax-default.xml

  If your device uses `Read-only` ROM, you must use the module version : https://github.com/adivenxnataly/DaxConfig/releases/tag/DaxConfig

  - then, you only need to replace the DaxConfig file manually, or you can do it directly in the root directory:
`/data/adb/modules/DaxConfig/system/vendor/etc/dolby/dax-default.xml`
  - and reboot.

 *does not cause softbrick or bootloop.
 
## Tested on (Stock ROM)
  - Android 12 - MIUI 13
  - Android 13 - MIUI 14
  - Android 14 - HyperOS 1.0
