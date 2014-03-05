PKGNAM = pkg-config
PKGVER = 0.28
PKGURL = http://pkgconfig.freedesktop.org/releases
PKGDIR = $(PKGNAM)-$(PKGVER)
PKGTAR = $(PKGDIR).tar.gz
PKGOUT = /bin/$(PKGNAM)

include ../../Include.mk

$(PLATFORM): source $(PACKAGE)
	@cd $@; ./configure --prefix=$(PREFIX) \
    --enable-indirect-deps \
    --with-internal-glib \
    --with-pc-path=$(PREFIX)/lib/pkgconfig:$(PREFIX)/share/pkgconfig
