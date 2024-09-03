# SPDX-License-Identifier: GPL-2.0

subdir-ccflags-y += -Werror

ccflags-y += -I$(srctree)/mtk-modules/drivers/gpu/drm/mediatek/dpc \
             -I$(srctree)/mtk-modules/drivers/gpu/drm/mediatek/mml \
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/mdp \
             -I$(srctree)/mtk-modules/drivers/gpu/drm/mediatek/mediatek_v2 \
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/cmdq/mailbox \
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/mmp \
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/mmdvfs \
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/smi \
             -I$(srctree)/mtk-modules/drivers/soc/mediatek

obj-$(CONFIG_MTK_DPC) := mtk_dpc.o

mtk_dpc-objs += mtk_dpc_driver.o
mtk_dpc-objs += mtk_dpc_mmp.o

obj-$(CONFIG_MTK_DPC) += mtk_vdisp.o
