# SPDX-License-Identifier: GPL-2.0
ifneq ($(CONFIG_MACH_XIAOMI_SDM660),y)
dtb-$(CONFIG_ARCH_QCOM)	+= k5pro-mtp.dtb

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
endif
