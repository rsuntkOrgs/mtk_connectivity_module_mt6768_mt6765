# Mediatek external kernel modules

> [!NOTE]
> Imported from SM-A055F/Platform.tar.gz/vendor/mediatek/kernel_modules/connectivity
>
> Supported platform: MT6765 and MT6768 (adding more support in the future)

> [!WARNING]
> This is currently untested. If errors occoured, please open a pull request or issue. Thank you.
>
> This driver is intended for 4.19.x not 4.14.x

# Mediatek required configurations
enable `CONFIG_MTK_COMBO_BT`, `CONFIG_MTK_COMBO_WIFI`, `CONFIG_MTK_COMBO_GPS`, `CONFIG_MTK_GPS_SUPPORT`, `CONFIG_MTK_FMRADIO`

# Build configurations
enable `CONFIG_WLAN_DRV_BUILD_IN` and `CONFIG_MTK_MODULE_FORCE_INLINE_FM_GPS` for inline building. disable if you want build it as external module.