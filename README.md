### Kernel-Info
Tag: `LNX.LA.3.7.3.c2-06500-8939.0-1`
Version: `linux-3.10.28-Kitkat`

### How to build
```bash
$ export ARCH=arm
$ export CROSS_COMPILE=/root/arm-eabi-4.7/bin/arm-eabi-
$ make msm8916_15005_defconfig
$ make -j6
```

### Output files
* Kernel
  * `arch/arm/boot/zImage`
* Modules
  * `drivers/*/*/*.ko`

### About dt.img
Using the `'arch/arm/dts/msm8916-mtp-15005.dtb'` to compile it.
