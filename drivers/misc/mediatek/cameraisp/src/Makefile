#include $(srctree)/drivers/misc/mediatek/Makefile.custom

obj-y := cameraisp_dummy.o

ifeq ($(CONFIG_ARCH_MT6580),y)
  obj-y += $(CONFIG_MTK_PLATFORM)/
endif

ifeq ($(CONFIG_ARCH_MT6735M),y)
  obj-y += $(CONFIG_MTK_PLATFORM)/
endif

ifeq ($(CONFIG_ARCH_MT6735),y)
  obj-y += $(CONFIG_MTK_PLATFORM)/
endif

ifeq ($(CONFIG_ARCH_MT6753),y)
  obj-y += $(CONFIG_MTK_PLATFORM)/
endif

#ifeq ($(CONFIG_ARCH_MT6795),y)
#  obj-y += $(CONFIG_MTK_PLATFORM)/
#endif

ifeq ($(CONFIG_ARCH_MT8163),y)
  obj-y += $(CONFIG_MTK_PLATFORM)/
endif

ifeq ($(CONFIG_ARCH_MT8173),y)
  obj-y += $(CONFIG_MTK_PLATFORM)/
endif

ifeq ($(CONFIG_ARCH_MT6797),y)
  obj-y += $(CONFIG_MTK_PLATFORM)/
endif


#this moment do not have other folder
#obj-y += $(subst ",,$(CONFIG_MTK_PLATFORM))/
