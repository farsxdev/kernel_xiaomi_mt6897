# SPDX-License-Identifier: GPL-2.0-only
$(warning build_test dummy_drm)

subdir-ccflags-y += -Werror
subdir-ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/include/
subdir-ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/include/mt-plat/


mediatek-dummy-drm-y := \
	mtk_vkms_composer.o \
	mtk_vkms_crtc.o \
	mtk_vkms_drv.o \
	mtk_vkms_helper.o \
	mtk_vkms_ioctls.o \
	mtk_vkms_output.o \
	mtk_vkms_plane.o \
	mtk_vkms_debug.o \
	mtk_vkms_mmp.o \
	mtk_vkms_writeback.o

obj-$(CONFIG_DRM_MEDIATEK_DUMMY) += mediatek-dummy-drm.o


obj-$(CONFIG_DEVICE_MODULES_DRM_MEDIATEK) += mtk_sync.o
obj-$(CONFIG_DEVICE_MODULES_DRM_MEDIATEK) += mtk_panel_ext.o
obj-$(CONFIG_DEVICE_MODULES_DRM_MEDIATEK) += mtk_disp_notify.o


ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/scp/include/
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/dramc/$(MTK_PLATFORM)	\
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/smi/			\
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/mmp/			\
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/mmdvfs/			\
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/pmic/			\
             -I$(srctree)/mtk-modules/drivers/iommu/				\
             -I$(srctree)/mtk-modules/drivers/devfreq/				\
             -I$(srctree)/drivers/gpu/drm/				\
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include/mach/				\
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/include/mt-plat/ \
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/leds/ \
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/leds/$(MTK_PLATFORM) \
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/cmdq/mailbox/        \
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/iommu/		\
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/mtk-interconnect/        \
             -I$(srctree)/drivers/gpu/drm/mediatek \
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/slbc/ \
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/cmdq/mailbox/ \
             -I$(srctree)/mtk-modules/drivers/misc/mediatek/clkbuf/v1/inc/ \
