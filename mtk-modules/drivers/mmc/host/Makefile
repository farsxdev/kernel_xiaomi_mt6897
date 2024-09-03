# SPDX-License-Identifier: GPL-2.0
#
# Makefile for MMC/SD host controller drivers
#
ccflags-y += -I$(srctree)/mtk-modules/drivers/char/rpmb/
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/include/
ccflags-y += -I$(srctree)/mtk-modules/drivers/ufs/
ccflags-y += -I$(srctree)/mtk-modules/drivers/mmc/host
ccflags-y += -I$(srctree)/drivers/ufs/
ccflags-y += -I$(srctree)/drivers/mmc/host/
ccflags-y += -I$(srctree)/include/ufs/

obj-$(CONFIG_DEVICE_MODULES_MMC_MTK)			+= mtk-sd.o
obj-$(CONFIG_MMC_MTK_PRO)		+= mtk-mmc.o
obj-$(CONFIG_DEVICE_MODULES_MMC_DEBUG)			+= mtk-mmc-dbg.o
obj-$(CONFIG_DEVICE_MODULES_MMC_CQHCI)			+= cqhci.o
cqhci-y					+= cqhci-core.o
cqhci-$(CONFIG_MMC_CRYPTO)		+= cqhci-crypto.o