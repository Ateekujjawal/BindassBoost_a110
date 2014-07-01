cd ~/DedS_a110/kernel
export ARCH=arm
export PATH=~/arm-linux-androdieabi-4.6/bin:$PATH
export CROSS_COMPILE=arm-linux-androideabi-
TARGET_PRODUCT=s9081 MTK_ROOT_CUSTOM=../mediatek/custom/ make clean
rm -r ~/DedS_a110/mtktools/temp/symbols
rm -r ~/DedS_a110/mtktools/temp/system
rm -r ~/DedS_a110/mtktools/BBFZ/system/lib/modules/*.ko
rm ~/DedS_a110/mtktools/BBFZ/boot.img
rm ~/DedS_a110/mtktools/zimage
