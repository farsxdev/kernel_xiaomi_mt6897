# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the phy drivers.
#

ccflags-y += -I$(srctree)/mtk-modules/drivers/ufs
ccflags-y += -I$(srctree)/mtk-modules/drivers/ufs/vendor
ccflags-y += -I$(srctree)/drivers/ufs

obj-$(CONFIG_PHY_MTK_FPGAPHY)		+= phy-mtk-fpgaphy.o
obj-$(CONFIG_DEVICE_MODULES_PHY_MTK_PCIE)		+= phy-mtk-pcie.o
obj-$(CONFIG_DEVICE_MODULES_PHY_MTK_TPHY)		+= phy-mtk-tphy.o
obj-$(CONFIG_DEVICE_MODULES_PHY_MTK_UFS)              += phy-mtk-ufs.o
obj-$(CONFIG_DEVICE_MODULES_PHY_MTK_XSPHY)		+= phy-mtk-xsphy.o
