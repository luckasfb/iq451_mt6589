export PATH=~/Your_Toolchain_PATH/
for example /alps/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.6/bin
USE_CCACHE=1

Build Command:
kernel
======
cd kernel directory
TARGET_PRODUCT=wiko MTK_ROOT_CUSTOM=../mediatek/custom/ make -j3
