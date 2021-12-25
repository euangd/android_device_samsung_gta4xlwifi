## Recovery Device Tree for the Samsung Galaxy Tab S6 Lite (Exynos)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_gta4xlwifi-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_gta4xlwifi
