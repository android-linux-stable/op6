#dtb-$(CONFIG_ARCH_QCOM)	+= apq8016-sbc.dtb msm8916-mtp.dtb
#dtb-$(CONFIG_ARCH_QCOM)	+= msm8996-mtp.dtb
#dtb-$(CONFIG_ARCH_QCOM)	+= apq8096-db820c.dtb
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
        enchilada-t0-v2.1-overlay.dtbo  \
	    enchilada-evt1-v2.1-overlay.dtbo \
	    enchilada-evt2-v2.1-overlay.dtbo \
	    enchilada-evt2-cxo-v2.1-overlay.dtbo \
		enchilada-dvt-v2.1-overlay.dtbo \
		enchilada-dvt-v2.1-backup-overlay.dtbo \
		enchilada-dvt-v2.1-usb30-overlay.dtbo \
		enchilada-pvt-v2.1-overlay.dtbo \
		enchilada-pvt-v2.1-backup-overlay.dtbo \
		enchilada-mp-v2.1-overlay.dtbo \
	    flan-evb-v2-overlay.dtbo \
        flan-evb-v2.1-overlay.dtbo 

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
flan-evb-v2-overlay.dtbo-base := sdm845-v2.dtb
flan-evb-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb


else ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),n)
		dtbo-$(CONFIG_ARCH_SDM845) += \
		sdm845-cdp-overlay.dtbo \
		sdm845-mtp-overlay.dtbo \
		sdm845-qrd-overlay.dtbo \
		sdm845-4k-panel-mtp-overlay.dtbo \
		sdm845-4k-panel-cdp-overlay.dtbo \
		sdm845-4k-panel-qrd-overlay.dtbo \
		sdm845-v2-qvr-overlay.dtbo \
		sdm845-v2-cdp-overlay.dtbo \
		sdm845-v2-mtp-overlay.dtbo \
		sdm845-v2-qrd-overlay.dtbo \
		sdm845-v2-4k-panel-mtp-overlay.dtbo \
		sdm845-v2-4k-panel-cdp-overlay.dtbo \
		sdm845-v2-4k-panel-qrd-overlay.dtbo \
		sdm845-v2.1-cdp-overlay.dtbo \
		sdm845-v2.1-mtp-overlay.dtbo \
		sdm845-v2.1-qrd-overlay.dtbo \
		sdm845-v2.1-4k-panel-mtp-overlay.dtbo \
		sdm845-v2.1-4k-panel-cdp-overlay.dtbo \
		sdm845-v2.1-4k-panel-qrd-overlay.dtbo \
		sda845-cdp-overlay.dtbo \
		sda845-mtp-overlay.dtbo \
		sda845-qrd-overlay.dtbo \
		sda845-4k-panel-mtp-overlay.dtbo \
		sda845-4k-panel-cdp-overlay.dtbo \
		sda845-4k-panel-qrd-overlay.dtbo \
		sda845-v2-cdp-overlay.dtbo \
		sda845-v2-mtp-overlay.dtbo \
		sda845-v2-qrd-overlay.dtbo \
		sda845-v2-hdk-overlay.dtbo \
		sda845-v2-svr-overlay.dtbo \
		sda845-v2-4k-panel-mtp-overlay.dtbo \
		sda845-v2-4k-panel-cdp-overlay.dtbo \
		sda845-v2-4k-panel-qrd-overlay.dtbo \
		sda845-v2.1-cdp-overlay.dtbo \
		sda845-v2.1-mtp-overlay.dtbo \
		sda845-v2.1-qrd-overlay.dtbo \
		sda845-v2.1-svr-overlay.dtbo \
		sda845-v2.1-4k-panel-cdp-overlay.dtbo \
		sda845-v2.1-4k-panel-mtp-overlay.dtbo \
		sda845-v2.1-4k-panel-qrd-overlay.dtbo

sdm845-cdp-overlay.dtbo-base := sdm845.dtb
sdm845-mtp-overlay.dtbo-base := sdm845.dtb
sdm845-qrd-overlay.dtbo-base := sdm845.dtb
sdm845-4k-panel-mtp-overlay.dtbo-base := sdm845.dtb
sdm845-4k-panel-cdp-overlay.dtbo-base := sdm845.dtb
sdm845-4k-panel-qrd-overlay.dtbo-base := sdm845.dtb
sdm845-v2-qvr-overlay.dtbo-base := sdm845-v2.dtb
sdm845-v2-cdp-overlay.dtbo-base := sdm845-v2.dtb
sdm845-v2-mtp-overlay.dtbo-base := sdm845-v2.dtb
sdm845-v2-qrd-overlay.dtbo-base := sdm845-v2.dtb
sdm845-v2-4k-panel-mtp-overlay.dtbo-base := sdm845-v2.dtb
sdm845-v2-4k-panel-cdp-overlay.dtbo-base := sdm845-v2.dtb
sdm845-v2-4k-panel-qrd-overlay.dtbo-base := sdm845-v2.dtb
sdm845-v2.1-cdp-overlay.dtbo-base := sdm845-v2.1.dtb
sdm845-v2.1-mtp-overlay.dtbo-base := sdm845-v2.1.dtb
sdm845-v2.1-qrd-overlay.dtbo-base := sdm845-v2.1.dtb
sdm845-v2.1-4k-panel-mtp-overlay.dtbo-base := sdm845-v2.1.dtb
sdm845-v2.1-4k-panel-cdp-overlay.dtbo-base := sdm845-v2.1.dtb
sdm845-v2.1-4k-panel-qrd-overlay.dtbo-base := sdm845-v2.1.dtb
sda845-cdp-overlay.dtbo-base := sda845.dtb
sda845-mtp-overlay.dtbo-base := sda845.dtb
sda845-qrd-overlay.dtbo-base := sda845.dtb
sda845-4k-panel-mtp-overlay.dtbo-base := sda845.dtb
sda845-4k-panel-cdp-overlay.dtbo-base := sda845.dtb
sda845-4k-panel-qrd-overlay.dtbo-base := sda845.dtb
sda845-v2-cdp-overlay.dtbo-base := sda845-v2.dtb
sda845-v2-mtp-overlay.dtbo-base := sda845-v2.dtb
sda845-v2-qrd-overlay.dtbo-base := sda845-v2.dtb
sda845-v2-hdk-overlay.dtbo-base := sda845-v2.dtb
sda845-v2-svr-overlay.dtbo-base := sda845-v2.dtb
sda845-v2-4k-panel-mtp-overlay.dtbo-base := sda845-v2.dtb
sda845-v2-4k-panel-cdp-overlay.dtbo-base := sda845-v2.dtb
sda845-v2-4k-panel-qrd-overlay.dtbo-base := sda845-v2.dtb
sda845-v2.1-cdp-overlay.dtbo-base := sda845-v2.1.dtb
sda845-v2.1-mtp-overlay.dtbo-base := sda845-v2.1.dtb
sda845-v2.1-qrd-overlay.dtbo-base := sda845-v2.1.dtb
sda845-v2.1-svr-overlay.dtbo-base := sda845-v2.1.dtb
sda845-v2.1-4k-panel-cdp-overlay.dtbo-base := sda845-v2.1.dtb
sda845-v2.1-4k-panel-mtp-overlay.dtbo-base := sda845-v2.1.dtb
sda845-v2.1-4k-panel-qrd-overlay.dtbo-base := sda845-v2.1.dtb
else
dtb-$(CONFIG_ARCH_SDM845) += sdm845-sim.dtb \
	sdm845-rumi.dtb \
	sdm845-mtp.dtb \
	sdm845-cdp.dtb \
	sdm845-v2-rumi.dtb \
	sdm845-v2-mtp.dtb \
	sdm845-v2-cdp.dtb \
	sdm845-qrd.dtb \
	sdm845-v2-qrd.dtb \
	sdm845-v2-qvr.dtb \
	sdm845-4k-panel-mtp.dtb \
	sdm845-4k-panel-cdp.dtb \
	sdm845-4k-panel-qrd.dtb \
	sdm845-interposer-sdm670-mtp.dtb \
	sdm845-interposer-sdm670-cdp.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
