SSC_BUILD_FOLDER=$(srctree)/mtk-modules/drivers/misc/mediatek/ssc

ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/include/
ccflags-y += -I$(srctree)/mtk-modules/drivers/misc/mediatek/tinysys_scmi/

# include gpu header
ccflags-y += -I$(srctree)/mtk-modules/drivers/gpu/mediatek/gpufreq/v2/include/

ccflags-y += -I$(SSC_BUILD_FOLDER)/inc/

SSC_MODULE += ssc_module.o

#Generic build
SSC_SRC = $(SSC_MODULE)
obj-$(CONFIG_MTK_SSC_MODULE) = mtk-ssc.o
mtk-ssc-objs += $(SSC_SRC)

#Generic subdir build
obj-$(CONFIG_MTK_SSC_MODULE) += debug/
