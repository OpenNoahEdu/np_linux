#
# Makefile for MMC/SD host controller drivers
#

ifeq ($(CONFIG_MMC_DEBUG),y)
	EXTRA_CFLAGS		+= -DDEBUG
endif

obj-$(CONFIG_MMC_JZ)		+= jz_mmc.o
obj-$(CONFIG_MSC0_JZ4750)	+= jz4750_mmc.o
obj-$(CONFIG_MSC1_JZ4750)	+= jz4750_mmc.o

obj-$(CONFIG_MMC_ARMMMCI)	+= mmci.o
obj-$(CONFIG_MMC_PXA)		+= pxamci.o
obj-$(CONFIG_MMC_IMX)		+= imxmmc.o
obj-$(CONFIG_MMC_MXC)		+= mxcmmc.o
obj-$(CONFIG_MMC_SDHCI)		+= sdhci.o
obj-$(CONFIG_MMC_SDHCI_PCI)	+= sdhci-pci.o
obj-$(CONFIG_MMC_RICOH_MMC)	+= ricoh_mmc.o
obj-$(CONFIG_MMC_SDHCI_OF)	+= sdhci-of.o
obj-$(CONFIG_MMC_SDHCI_PLTFM)	+= sdhci-pltfm.o
obj-$(CONFIG_MMC_SDHCI_S3C)	+= sdhci-s3c.o
obj-$(CONFIG_MMC_WBSD)		+= wbsd.o
obj-$(CONFIG_MMC_AU1X)		+= au1xmmc.o
obj-$(CONFIG_MMC_OMAP)		+= omap.o
obj-$(CONFIG_MMC_OMAP_HS)	+= omap_hsmmc.o
obj-$(CONFIG_MMC_AT91)		+= at91_mci.o
obj-$(CONFIG_MMC_ATMELMCI)	+= atmel-mci.o
obj-$(CONFIG_MMC_TIFM_SD)	+= tifm_sd.o
obj-$(CONFIG_MMC_MVSDIO)	+= mvsdio.o
obj-$(CONFIG_MMC_SPI)		+= mmc_spi.o
ifeq ($(CONFIG_OF),y)
obj-$(CONFIG_MMC_SPI)		+= of_mmc_spi.o
endif
obj-$(CONFIG_MMC_S3C)   	+= s3cmci.o
obj-$(CONFIG_MMC_SDRICOH_CS)	+= sdricoh_cs.o
obj-$(CONFIG_MMC_TMIO)		+= tmio_mmc.o
obj-$(CONFIG_MMC_CB710)	+= cb710-mmc.o
obj-$(CONFIG_MMC_VIA_SDMMC)	+= via-sdmmc.o

ifeq ($(CONFIG_CB710_DEBUG),y)
	CFLAGS-cb710-mmc	+= -DDEBUG
endif
