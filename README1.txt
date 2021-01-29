Default Configuration for Zynq Zc706

See the below steps:
1.      
        make zc706_defconfig  (vim configs/zc706_defconfig)
        make menuconfig
        make busybox-menuconfig 
        make linux-menuconfig
2.      
        make (will take few minutes)
3.
        Generated images are populated in output/images  path
~                                                     
