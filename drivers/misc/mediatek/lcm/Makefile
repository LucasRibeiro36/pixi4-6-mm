#
# Makefile for misc devices that really don't fit anywhere else.
#

obj-y += mt65xx_lcm_list.o

LCM_LISTS := $(subst ",,$(CONFIG_CUSTOM_KERNEL_LCM))
obj-y += $(foreach LCM,$(LCM_LISTS),$(LCM)/)
