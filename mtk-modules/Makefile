# SPDX-License-Identifier: GPL-2.0

# Set KERNEL_SRC to mtk-modules so that the include paths are set correctly
# for in-tree compilation, since the modules assume that `mtk-modules` exists
# in the same directory as the kernel tree (one level up), whereas we've got
# `mtk-modules` inside the kernel tree. This way, when the modules include
# with `-I$(KERNEL_SRC)/../mtk-modules/SOME_MODULE`, inclusion works as-is.
export KERNEL_SRC := $(srctree)/mtk-modules

export LINUXINCLUDE += -I$(srctree)/mtk-modules/include

subdir-ccflags-y += \
	-I$(srctree)/mtk-modules/include \
	-I$(srctree)/mtk-modules/include/uapi

obj-y += arch/arm64/geniezone/
obj-y += drivers/char/
obj-y += drivers/clk/mediatek/
obj-y += drivers/clocksource/
obj-y += drivers/cpufreq/
obj-y += drivers/devfreq/
obj-y += drivers/dma-buf/heaps/
obj-y += drivers/dma/mediatek/
obj-y += drivers/gpu/drm/mediatek/
obj-y += drivers/gpu/drm/panel/
obj-y += drivers/gpu/mediatek/
obj-y += drivers/i2c/busses/
obj-y += drivers/iio/adc/
obj-y += drivers/input/fingerprint/
obj-y += drivers/input/keyboard/
obj-y += drivers/input/misc/
obj-y += drivers/input/touchscreen/
obj-y += drivers/interconnect/
obj-y += drivers/iommu/
obj-y += drivers/leds/
obj-y += drivers/mailbox/
obj-y += drivers/media/platform/
obj-y += drivers/memory/
obj-y += drivers/mfd/
obj-y += drivers/misc/mediatek/
obj-y += drivers/misc/xiaomi/
obj-y += drivers/mmc/host/
obj-y += drivers/nvmem/
obj-y += drivers/pci/controller/
obj-y += drivers/phy/mediatek/
obj-y += drivers/pinctrl/mediatek/
obj-y += drivers/power/supply/
obj-y += drivers/pwm/
obj-y += drivers/regulator/
obj-y += drivers/remoteproc/
obj-y += drivers/reset/
obj-y += drivers/rpmsg/
obj-y += drivers/rtc/
obj-y += drivers/soc/mediatek/
obj-y += drivers/spi/
obj-y += drivers/spmi/
obj-y += drivers/staging/process_exit/
obj-y += drivers/tee/
obj-y += drivers/thermal/mediatek/
obj-y += drivers/tty/serial/8250/
obj-y += drivers/ufs/
obj-y += drivers/usb/
obj-y += drivers/watchdog/
obj-y += sound/soc/codecs/
obj-y += sound/soc/mediatek/
