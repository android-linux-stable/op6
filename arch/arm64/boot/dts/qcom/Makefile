ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_SDM845) += \
        sdm845-mtp-overlay.dtbo \
        sdm845-v2-mtp-overlay.dtbo \
        sdm845-v2.1-mtp-overlay.dtbo \
        enchilada-evb-overlay.dtbo \
        enchilada-evb-v2-overlay.dtbo \
        enchilada-evb-v2.1-overlay.dtbo \
        enchilada-t0-v2-overlay.dtbo \
        enchilada-evt1-v2-overlay.dtbo \
        enchilada-evt2-v2-overlay.dtbo \
        enchilada-evt2-cxo-v2-overlay.dtbo \
        enchilada-dvt-v2-overlay.dtbo \
        enchilada-pvt-v2-overlay.dtbo \
        enchilada-mp-v2-overlay.dtbo  \
        enchilada-t0-v2.1-overlay.dtbo \
        enchilada-evt1-v2.1-overlay.dtbo \
        enchilada-evt2-v2.1-overlay.dtbo \
        enchilada-evt2-cxo-v2.1-overlay.dtbo \
        enchilada-dvt-v2.1-overlay.dtbo \
        enchilada-dvt-v2.1-backup-overlay.dtbo \
        enchilada-dvt-v2.1-usb30-overlay.dtbo \
        enchilada-pvt-v2.1-overlay.dtbo \
        enchilada-pvt-v2.1-backup-overlay.dtbo \
        enchilada-mp-v2.1-overlay.dtbo 


sdm845-mtp-overlay.dtbo-base := sdm845.dtb
sdm845-v2-mtp-overlay.dtbo-base := sdm845-v2.dtb
sdm845-v2.1-mtp-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-evb-overlay.dtbo-base := sdm845.dtb
enchilada-evb-v2-overlay.dtbo-base := sdm845-v2.dtb
enchilada-evb-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-t0-v2-overlay.dtbo-base := sdm845-v2.dtb
enchilada-evt1-v2-overlay.dtbo-base := sdm845-v2.dtb
enchilada-evt2-v2-overlay.dtbo-base := sdm845-v2.dtb
enchilada-evt2-cxo-v2-overlay.dtbo-base := sdm845-v2.dtb
enchilada-dvt-v2-overlay.dtbo-base := sdm845-v2.dtb
enchilada-pvt-v2-overlay.dtbo-base := sdm845-v2.dtb
enchilada-mp-v2-overlay.dtbo-base := sdm845-v2.dtb
enchilada-t0-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-evt1-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-evt2-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-evt2-cxo-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-dvt-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-dvt-v2.1-backup-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-dvt-v2.1-usb30-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-pvt-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-pvt-v2.1-backup-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-mp-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
