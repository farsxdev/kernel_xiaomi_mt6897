# SPDX-License-Identifier: GPL-2.0-only
#
# Main Makefile for gzvm, this one includes drivers/virt/geniezone/Makefile
#
ccflags-y += -I$(srctree)/mtk-modules/include/uapi
ccflags-y += -I$(srctree)/mtk-modules/arch/arm64/include/uapi
ccflags-y += -I$(srctree)/mtk-modules/include

include $(srctree)/mtk-modules/drivers/virt/geniezone/Makefile

gzvm-y += vm.o vcpu.o vgic.o driver.o

obj-$(CONFIG_MTK_GZVM) += gzvm.o
