PKG_NAME = pyload
PKG_VERS = 0.4.9
PKG_EXT = zip
PKG_DIST_NAME = $(PKG_NAME)-src-v$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://download.pyload.org
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS =

HOMEPAGE = http://www.pyload.org/
COMMENT  = One-Click Hoster downloader
LICENSE  = GPL

CONFIGURE_TARGET = nop
COMPILE_TARGET = nop
INSTALL_TARGET = myInstall

include ../../mk/spksrc.cross-cc.mk

myInstall:
	mkdir -p $(STAGING_INSTALL_PREFIX)/share/pyLoad
	cp -r $(WORK_DIR)/$(PKG_NAME)/* $(STAGING_INSTALL_PREFIX)/share/pyLoad/
