# SPDX-License-Identifier: GPL-2.0
# UFSHCD makefile
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/include/
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/blocktag/
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/power_throttling/
ccflags-y += -I$(srctree)/mtk-modules/drivers/ufs/vendor
ccflags-y += -I$(srctree)/mtk-modules/drivers/ufs/
ccflags-y += -I$(srctree)/drivers/ufs/core/
ccflags-y += -I$(srctree)/drivers/ufs/host/
ccflags-y += -I$(srctree)/drivers/devfreq/
ccflags-y += -I$(srctree)/kernel/

obj-$(CONFIG_DEVICE_MODULES_SCSI_UFS_MEDIATEK) += vendor/
obj-$(CONFIG_SCSI_UFS_MEDIATEK_DBG) += ufs-mediatek-dbg.o
