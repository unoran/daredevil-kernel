Daredevil Kernel
==============

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | 1.5GHz 64-bit Octa-Core MT6752
GPU     | Mali-T760MP2
Memory  | 2GB RAM
Android Version | 6.0
Storage | 8GB
Display | 5.5" IPS 1280 x 720 px
Camera  | 8MPx, LED Flash

* Compilation
        
        $ export CROSS_COMPILE=aarch64-linux-android-

        $ export PATH=~/toolchains/aarch64-linux-android-x.x/bin:$PATH

        $ export ARCH=arm64

        $ make aio_row_defconfig ARCH=arm64 CROSS_COMPILE=aarch64-linux-android-

        $ make ARCH=arm64 CROSS_COMPILE=aarch64-linux-android-



