export PATH=~/Your_Toolchain_PATH/
for example /alps/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.6/bin
USE_CCACHE=1

Build Command:
kernel IQ451 Vista
======
cd kernel directory
TARGET_PRODUCT=wiko 
export MTK_ROOT_CUSTOM=../mediatek/custom/ MTK_PATH_SOURCE=../mediatek/kernel/ MTK_PATH_PLATFORM=../mediatek/platform/mt6589/kernel/ ARCH_MTK_PLATFORM=mt6589 make

Build Command:
kernel IQ450 Quattro Horizon 2
======
cd kernel directory
TARGET_PRODUCT=s9086b 
export MTK_ROOT_CUSTOM=../mediatek/custom/ MTK_PATH_SOURCE=../mediatek/kernel/ MTK_PATH_PLATFORM=../mediatek/platform/mt6589/kernel/ ARCH_MTK_PLATFORM=mt6589 make
