# bios_qemu_tz_arm

添加对vexpress-a15(vexpress-v2p-ca15-tc1)平台支持，平台参数来自

http://infocenter.arm.com/help/topic/com.arm.doc.den0001c/DEN0001C_principles_of_arm_memory_maps.pdf

## 编译
```shell
make CROSS_COMPILE=arm-linux-gnueabihf-  O=../out/bios-qemu PLATFORM_FLAVOR=vexpress
```
