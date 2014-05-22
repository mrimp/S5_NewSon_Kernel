S5_NewSon_Kernel
================

****************************************************

1. How to Build

- get Toolchain SaberMod Toolchain 4.9.0

- Build
		$ sudo su
		$ export ARCH=arm
		$ export CROSS_COMPILE=/home/mrimp/android/toolchain/sm-arm-eabi-4.9/bin/arm-eabi-
		$ make msm8974_sec_defconfig VARIANT_DEFCONFIG=msm8974pro_sec_klte_eur_defconfig SELINUX_DEFCONFIG=selinux_defconfig
		$ make

****************************************************
