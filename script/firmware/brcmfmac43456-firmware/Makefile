
GARNAME       = brcmfmac43456-firmware
GARVERSION    = 056d5f6776e515f90bbbbead1be06857aaef17d0
CATEGORIES    = firmware
MASTER_SITES  = https://gitlab.manjaro.org/manjaro-arm/packages/community/ap6256-firmware/-/archive/$(GARVERSION)/
DISTFILES     = ap6256-firmware-$(GARVERSION).tar.bz2
LICENSE       =
DESCRIPTION   =

WORKSRC = $(WORKDIR)/ap6256-firmware-$(GARVERSION)

define BLURB
endef

DEPENDS = lang/c

INSTALL_SCRIPTS = custom

include ../../gar.mk

install-custom:
	@cp -f   $(WORKSRC)/brcmfmac43456-sdio.AP6256.txt $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.txt
	@cp -f   $(WORKSRC)/fw_bcm43456c5_ag.bin          $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.bin
	@cp -f   $(WORKSRC)/brcmfmac43456-sdio.clm_blob   $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.clm_blob
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.txt       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.radxa,rockpi4b.txt
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.txt       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.radxa,rockpi4c.txt
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.txt       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.radxa,zero.txt
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.txt       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.radxa,zero2.txt
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.txt       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.pine64,pinebook-pro.txt
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.txt       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.pine64,rockpro64-v2.1.txt
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.txt       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.rockchip,rk3399-orangepi.txt
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.txt       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.xunlong,orangepi-3.txt
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.txt       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.xunlong,orangepi-4.txt
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.txt       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.xunlong,quartz64-a.txt
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.txt       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.xunlong,quartz64-b.txt
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.bin       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.radxa,rockpi4b.bin
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.bin       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.radxa,rockpi4c.bin
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.bin       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.radxa,zero.bin
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.bin       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.radxa,zero2.bin
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.bin       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.pine64,pinebook-pro.bin
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.bin       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.pine64,rockpro64-v2.1.bin
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.bin       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.rockchip,rk3399-orangepi.bin
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.bin       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.xunlong,orangepi-3.bin
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.bin       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.xunlong,orangepi-4.bin
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.bin       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.xunlong,quartz64-a.bin
	@ln -srf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.bin       $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456-sdio.xunlong,quartz64-b.bin
	@$(MAKECOOKIE)

clean-all: clean
	@rm -rf $(DESTDIR)$(elibdir)/firmware/brcm/brcmfmac43456*
