## Xaga Project - Personal extras
<img align="right" width="180" height="180" src="https://cdn.cnbj0.fds.api.mi-img.com/b2c-shopapi-pms/pms_1653384568.5698588.png">

This organization contains repositories to build AOSP ROMs for POCO X4 GT / Redmi K50i / Redmi Note 11T Pro(+) (xaga)

### Required device specific repositories
* [**Device Tree (xaga)**](https://github.com/xaga-dev/android_device_xiaomi_xaga.git) (`android_device_xiaomi_xaga`)
* [**Device Tree (common)**](https://github.com/xaga-dev/android_device_xiaomi_mt6895-common.git) (`android_device_xiaomi_mt6895-common`)
* [**Vendor Tree (xaga)**](https://gitlab.com/angxddeep/proprietary_vendor_xiaomi_xaga) (`proprietary_vendor_xiaomi_xaga`)
* [**Vendor Tree (common)**](https://gitlab.com/angxddeep/proprietary_vendor_xiaomi_mt6895-common) (`proprietary_vendor_xiaomi_mt6895-common`)
* [**Kernel Sources**](https://github.com/xaga-dev/android_kernel_xiaomi_mt6895.git) (`android_kernel_xiaomi_mt6895`)

### Other required repositories
* [**Mediatek Sepolicy**](https://github.com/Lineageos/android_device_mediatek_sepolicy_vndr.git) (`android_device_mediatek_sepolicy_vndr`)
* [**Mediatek Hardware**](https://github.com/Lineageos/android_hardware_mediatek.git) (`android_hardware_mediatek`)
* [**Xiaomi Hardware**](https://github.com/Lineageos/android_hardware_xiaomi.git) (`android_hardware_xiaomi`)
* [**MiuiCamera Device Tree**](https://github.com/xaga-dev/android_device_xiaomi_miuicamera-xaga) (`android_device_xiaomi_miuicamera-xaga`)
* [**MiuiCamera Vendor Tree**](https://gitlab.com/angxddeep/proprietary_vendor_xiaomi_miuicamera-xaga) (`proprietary_vendor_xiaomi_miuicamera-xaga`)


### Required patches
* [**Return false for GetDeviceLockStatus() if fenrir=true**](https://github.com/xaga-dev/android_system_core/commit/f443c69db2291f7c156be86ba21ee0d7543ab4e7) (`android_system_core`)
* [**Add xiaomi packages to the whitelist**](https://github.com/xaga-dev/android_build_soong/commit/fd57a35469af2616f6378bc53516c8c648215f91) (`android_build_soong`)