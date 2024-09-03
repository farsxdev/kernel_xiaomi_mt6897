MTK_PLATFORM := $(subst ",,$(CONFIG_MTK_CAMERA_ISP_PLATFORM)

$(info $(srctree)/mtk-modules)
#ifdef CONFIG_MTK_M4U
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/m4u/$(MTK_PLATFORM)/
#else
ccflags-y += -I$(srctree)/mtk-modules/drivers/iommu/
#endif
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/mmp/
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/cmdq/mailbox/
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/cmdq/v3/
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/cmdq/v3/$(MTK_PLATFORM)/
ccflags-y += -I$(srctree)/mtk-modules/drivers/staging/android/ion \
             -I$(srctree)/mtk-modules/drivers/staging/android/ion/mtk
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/smi/

obj-y += camera_fdvt.o

