ccflags-y += -I$(srctree)/$(src)              # needed for trace events
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/qos/

subdir-ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/include
subdir-ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/sched/
subdir-ccflags-y += -I$(srctree)/mtk-modules/drivers/thermal/mediatek/
subdir-ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/include/mt-plat/
subdir-ccflags-y += -I$(srctree)/mtk-modules/drivers/ufs
subdir-ccflags-y += -I$(srctree)/drivers/ufs

obj-$(CONFIG_MTK_PERF_COMMON) += mtk_perf_common.o
mtk_perf_common-y += perf_common.o
# a tracker for performance index
mtk_perf_common-$(CONFIG_MTK_PERF_TRACKER)+= perf_tracker.o
# a tracker for freq hook
mtk_perf_common-$(CONFIG_MTK_PERF_TRACKER)+= perf_freq_tracker.o
