## AOSP development for the Redmi Note 11S 4G and POCO M4 Pro 4G codenamed `fleur`

### Required Hardware/SEPolicy repositories
* [**MediaTek SEPolicy**](https://github.com/mt6781-devs/android_device_mediatek_sepolicy_vndr) (`android_device_mediatek_sepolicy_vndr`)
* [**MediaTek Hardware**](https://github.com/mt6781-devs/android_hardware_mediatek) (`android_hardware_mediatek`)
* [**MediaTek IMS**](https://github.com/mt6781-devs/android_vendor_mediatek_ims) (`android_vendor_mediatek_ims`)
* [**Xiaomi Hardware**](https://github.com/claxten10/android_hardware_xiaomi) (`android_hardware_xiaomi`)

### Required patches
* [**For fixing mediaserver crash after Android 16**](https://github.com/mt6878-devs/android_frameworks_av/commit/283f6151a83541ff5a262e02d053ecf76486a4d2) (`android_frameworks_av`)
* [**For fixing WPA3**](https://github.com/mt6781-devs/android_external_wpa_supplicant_8/commit/e181392193e82a13b2567583b934868591014c15) (`android_external_wpa_supplicant_8`)
* [**For 60FPS recording in Aperture**](https://github.com/Nothing-2A/android_packages_apps_Aperture/commit/a4c34aa57ed56de60f29349a1e6d20cf8160ca15) (`android_packages_apps_Aperture`)
