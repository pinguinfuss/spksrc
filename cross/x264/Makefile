PKG_NAME = x264
PKG_VERS = 20130719
PKG_EXT = tar.bz2
PKG_DIST_NAME = $(PKG_NAME)-snapshot-$(PKG_VERS)-2245-stable.$(PKG_EXT)
PKG_DIST_SITE = http://download.videolan.org/pub/videolan/$(PKG_NAME)/snapshots
PKG_DIR = $(PKG_NAME)-snapshot-$(PKG_VERS)-2245-stable

PATCHES_LEVEL=1
DEPENDS = 

HOMEPAGE = http://www.videolan.org/developers/x264.html
COMMENT  = x264 is a free software library and application for encoding video streams into the H.264/MPEG-4 AVC format.
LICENSE  = GPL

CONFIGURE_ARGS  = --disable-asm --enable-shared --enable-static
GNU_CONFIGURE = 1

include ../../mk/spksrc.cross-cc.mk
