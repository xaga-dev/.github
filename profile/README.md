## Development for POCO X4 GT / Redmi Note 11T Pro (+) / K50i "`xaga`"

<div>
  <img align="right" width="35%" src="https://cdn.cnbj0.fds.api.mi-img.com/b2c-shopapi-pms/pms_1653384568.5698588.png">
</div>

This organization contains all the important repositories required to build custom ROMs for POCO X4 GT / Redmi Note 11T Pro (+) / K50i

### Required device specific repositories
* [**Device tree**](https://github.com/xaga-dev/android_device_xiaomi_xaga) (`android_device_xiaomi_xaga`)
* [**Device tree (common)**](https://github.com/xaga-dev/android_device_xiaomi_mt6895-common) (`android_device_xiaomi_mt6895-common`)
* [**Vendor tree (xaga)**](https://gitlab.com/angxddeep/android_vendor_xiaomi_xaga) (`android_vendor_xiaomi_xaga`)
* [**Vendor tree (common)**](https://gitlab.com/angxddeep/android_vendor_xiaomi_mt6895-common) (`android_vendor_xiaomi_mt6895-common`)
* [**Device kernel tree**](https://github.com/xaga-dev/android_kernel_xiaomi_mt6895) (`android_kernel_xiaomi_mt6895`)

### Other required repositories
* [**MediaTek sepolicy**](https://github.com/LineageOS/android_device_mediatek_sepolicy_vndr) (`android_device_mediatek_sepolicy_vndr`)
* [**MediaTek hardware**](https://github.com/LineageOS/android_hardware_mediatek) (`android_hardware_mediatek`)
* [**Xiaomi Hardware**](https://github.com/LineageOS/android_hardware_xiaomi.git) (`android_hardware_xiaomi`)

### Required patches
* [**Return false for GetDeviceLockStatus() if fenrir=true**](https://github.com/XagaForge/android_system_core/commit/f443c69db2291f7c156be86ba21ee0d7543ab4e7) (`android_system_core`)
* [**Add xiaomi packages to the whitelist**](https://github.com/XagaForge/android_build_soong/commit/fd57a35469af2616f6378bc53516c8c648215f91) (`android_build_soong`)
* [**Whitelist Camera Extensions**](https://github.com/XagaForge/android_build_soong/commit/dcf3f8a9e601cd4cc220984e8b3c402f143aa843) (`android_build_soong`)