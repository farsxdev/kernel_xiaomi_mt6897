# SPDX-License-Identifier: GPL-2.0

ccflags-y += -I$(srctree)/drivers/remoteproc

obj-$(CONFIG_MTK_CCU_RPROC)		+= mtk_ccu.o
obj-$(CONFIG_MTK_CCU_RPROC)		+= mtk_ccu_mssv.o
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/mtk-interconnect/ \
			 -I$(srctree)/mtk-modules/drivers/misc/mediatek/include \
			 -I$(srctree)/mtk-modules/drivers/misc/mediatek/iommu \
			 -I$(srctree)/mtk-modules/drivers/iommu/arm/arm-smmu-v3 \
			 -I$(srctree)/mtk-modules/drivers/dma-buf/heaps

mtk_ccu-objs += mtk_ccu_isp71.o mtk_ccu_common.o mtk_ccu_ipi.o
mtk_ccu_mssv-objs += mtk_ccu_isp71_mssv.o mtk_ccu_common_mssv.o mtk_ccu_ipi_mssv.o
