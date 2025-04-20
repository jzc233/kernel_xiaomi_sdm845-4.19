ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-y += \
		sdm845-mtp-overlay.dtbo \
		sdm845-v2-mtp-overlay.dtbo \
		sdm845-v2.1-mtp-overlay.dtbo

dtb-$(CONFIG_MACH_XIAOMI_E10) := xiaomi/beryllium/beryllium-mp-v2.1.dtb
dtb-$(CONFIG_MACH_XIAOMI_D5X) += xiaomi/polaris/polaris-p0.dtb \
			xiaomi/polaris/polaris-p0-v2.dtb \
			xiaomi/polaris/polaris-p1.dtb \
			xiaomi/polaris/polaris-p1-v2.dtb \
			xiaomi/polaris/polaris-p1-v2.1.dtb \
			xiaomi/polaris/polaris-p2.dtb \
			xiaomi/polaris/polaris-p2-v2.dtb \
			xiaomi/polaris/polaris-p2-v2.1.dtb \
			xiaomi/polaris/polaris-p3.dtb \
			xiaomi/polaris/polaris-p3-v2.dtb \
			xiaomi/polaris/polaris-p3-v2.1.dtb \
			xiaomi/polaris/polaris-mp.dtb \
			xiaomi/polaris/polaris-mp-v2.dtb \
			xiaomi/polaris/polaris-mp-v2.1.dtb

dtb-$(CONFIG_MACH_XIAOMI_E1N) += xiaomi/dipper/dipper-p0-v2.dtb \
                        xiaomi/dipper/dipper-p0-v2.1.dtb \
                        xiaomi/dipper/dipper-p1.1-v2.dtb \
                        xiaomi/dipper/dipper-p1.1-v2.1.dtb \
                        xiaomi/dipper/dipper-p1-v2-gb.dtb \
                        xiaomi/dipper/dipper-p1-v2-cn.dtb \
                        xiaomi/dipper/dipper-p1-v2.1-gb.dtb \
                        xiaomi/dipper/dipper-p1-v2.1-cn.dtb \
                        xiaomi/dipper/dipper-p2-v2.dtb \
                        xiaomi/dipper/dipper-p2-v2.1.dtb \
                        xiaomi/dipper/dipper-mp-v2.dtb \
                        xiaomi/dipper/dipper-mp-v2.1.dtb


sdm845-mtp-overlay.dtbo-base := sdm845.dtb
sdm845-v2-mtp-overlay.dtbo-base := sdm845-v2.dtb
sdm845-v2.1-mtp-overlay.dtbo-base := sdm845-v2.1.dtb

polaris-p0-overlay.dtbo-base := sdm845.dtb
polaris-p0-v2-overlay.dtbo-base := sdm845-v2.dtb
polaris-p1-overlay.dtbo-base := sdm845.dtb
polaris-p1-v2-overlay.dtbo-base := sdm845-v2.dtb
polaris-p1-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
polaris-p2-overlay.dtbo-base := sdm845.dtb
polaris-p2-v2-overlay.dtbo-base := sdm845-v2.dtb
polaris-p2-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
polaris-p3-overlay.dtbo-base := sdm845.dtb
polaris-p3-v2-overlay.dtbo-base := sdm845-v2.dtb
polaris-p3-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb

dipper-p0-v2-overlay.dtbo-base := sdm845-v2.dtb
dipper-p0-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
dipper-p1-v2-overlay.dtbo-base := sdm845-v2.dtb
dipper-p1-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
dipper-p2-v2-overlay.dtbo-base := sdm845-v2.dtb
dipper-p2-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb

beryllium-p0-v2-overlay.dtbo-base := sdm845-v2.dtb
beryllium-p0-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb

endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
