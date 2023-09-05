testdisk.img.gz is a simple ext2 fs with busybox, iotools, kvm kselftests,
and kvm unit tests; qemu.img.gz adds a static build of qemu.

This is very useful for fast Linux kernel development and tests - you can
build a kernel with PVH support and have qemu boot it (via -kernel); the
images here give you a simple userspace to test with.
