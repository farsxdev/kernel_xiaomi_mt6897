subdir-ccflags-y += -Werror
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/smi
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/cmdq
mtk-vcu-y += mtk_vcu.o \
	mtk_vcodec_mem.o \

obj-$(CONFIG_VIDEO_MEDIATEK_VCU) += mtk-vcu.o
ccflags-y += -I$(srctree)/mtk-modules/arch/arm
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/include/mt-plat
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/vcp/rv
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/vcp/include
