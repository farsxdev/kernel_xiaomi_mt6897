# SPDX-License-Identifier: GPL-2.0
# Generic MAILBOX API

ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/cmdq/mailbox

ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/include

obj-$(CONFIG_DEVICE_MODULES_MTK_CMDQ_MBOX)	+= mtk-cmdq-mailbox.o

obj-$(CONFIG_MTK_TINYSYS_MBOX)    += mtk-mbox-mailbox.o

obj-$(CONFIG_MTK_ISE_MBOX)	+= mtk-ise-mailbox.o
