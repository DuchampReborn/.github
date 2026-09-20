
### Development for Poco X6 Pro 5G/Redmi K70E "`Duchamp`"
##### IMPORTANT: This org might not always be up to date, and some stuff will be broken.
#### For stable sources check [MT6897-devs Org](http://https://github.com/mt6897-devs "MT6897 Org")
<p align="center">
  <img width="40%" src="https://fdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-redmi-k70e-1.jpg">
<p align="center"> <img src="https://img.shields.io/badge/codename-duchamp-blueviolet"> <img src="https://img.shields.io/badge/chipset-MT6897%20%2F%20Dimensity%208300%20Ultra-blue"> <img src="https://img.shields.io/badge/platform-AOSP-brightgreen"> </p>
</p>

### Required device specific repositories
- [**Device tree**](https://github.com/DuchampReborn/device_xiaomi_duchamp) (`device_xiaomi_duchamp`)
- [**Device kernel tree (Compiled outputs from kernel source)**](https://github.com/mt6897-devs/device_xiaomi_duchamp-kernel) (`device_xiaomi_duchamp-kernel`)
### Other required repositories
- [**MediaTek sepolicy**](https://github.com/mt6897-devs/device_mediatek_sepolicy_vndr) (`device_mediatek_sepolicy_vndr`)
- [**MediaTek hardware**](https://github.com/LineageOS/android_hardware_mediatek) (`hardware_mediatek`)
- [**Xiaomi hardware**](https://github.com/mt6897-devs/hardware_xiaomi) (`hardware_xiaomi`)

### Required patches
- [**Aperture**](https://github.com/DuchampReborn/android_packages_apps_Aperture/commits/lineage-23.0/) (`packages_apps_Aperture`)
- [**Bluetooth**](https://github.com/DuchampReborn/packages_modules_Bluetooth/commit/59900cff7135e20e613c646c6c33fca2baa0acb0) (`packages_modules_Bluetooth`)
- [**WPA Supplicant**](https://github.com/DuchampReborn/android_external_wpa_supplicant_8/commits/lineage-23.1/) (`external_wpa_supplicant_8`)
- [**Frameworks Native**](https://github.com/DuchampReborn/frameworks_native/commits/17/) (`frameworks_native`)

### Extra Repos
- [**Dolby Atmos**](https://github.com/DuchampReborn/hardware_dolby) (`hardware_dolby`)
- [**GameBar**](https://github.com/DuchampReborn/android_packages_apps_GameBar) (`packages_apps_GameBar`)
- [**Engineering Mode DT**](https://github.com/DuchampReborn/device_xiaomi_duchamp-engineering) (`device_xiaomi_duchamp-engineering`)
- [**Engineering Mode Vendor**](https://github.com/DuchampReborn/vendor_xiaomi_duchamp-engineering) (`vendor_xiaomi_duchamp-engineering`)

### Device kernel repositories
- [**Kernel sources**](https://github.com/mt6897-devs/kernel_manifest) (`kernel_manifest`)

Optional flags:

```make
TARGET_INCLUDES_DOLBY := true
```


<p align="center"> <a href="https://t.me/luxured"> <img src="https://img.shields.io/badge/Telegram-Contact%20Me-blue?logo=telegram&logoColor=white"> </a> </p>
