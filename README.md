# kbase-valhall

Valhall kbase for faking a lODx (Mali-G610, used in RK3588) GPU.

Usage:

```
$ make -j`nproc` -C drivers/gpu/arm
$ sudo insmod drivers/gpu/arm/midgard/mali_kbase.ko
```

Grab blob drivers from here: (look for `libmali-valhall-g610-g6p0-*`)

https://github.com/JeffyCN/rockchip_mirrors/tree/libmali/lib/aarch64-linux-gnu
