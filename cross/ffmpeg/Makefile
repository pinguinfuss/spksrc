PKG_NAME = ffmpeg
PKG_VERS = 2.0
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://www.ffmpeg.org/releases
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS = cross/lame cross/x264 cross/faac

HOMEPAGE = http://www.ffmpeg.org
COMMENT  = 
LICENSE  = GPL2

CONFIGURE_ARGS  = --enable-gpl --enable-nonfree --enable-pthreads 
CONFIGURE_ARGS += --enable-libx264 --enable-libfaac --enable-libmp3lame
CONFIGURE_ARGS += --enable-cross-compile
GNU_CONFIGURE = 1

include ../../mk/spksrc.cross-cc.mk
