misc qemu for Raspberry PI emulation with megatree LED configuration - baremetal 


Debug example:
gdb-multiarch u-boot -ex "target remote localhost:1234"

qemu with debug:
qemu-system-aarch64 -M raspi3 -S -s -kernel u-boot -m 256


