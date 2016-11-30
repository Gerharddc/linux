# Overlays for the Raspberry Pi platform

dtbo-$(CONFIG_ARCH_BCM2835) += \
	vc4-kms-v3d.dtbo

targets += dtbs dtbs_install
targets += $(dtbo-y)

always		:= $(dtbo-y)
clean-files	:= *.dtbo
