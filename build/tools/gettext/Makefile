PKGNAM = gettext
PKGVER = 0.18.3.2
PKGURL = http://ftp.gnu.org/gnu/gettext
PKGDIR = $(PKGNAM)-$(PKGVER)
PKGTAR = $(PKGDIR).tar.gz
PKGOUT = /bin/gettext

include ../../Include.mk

$(PLATFORM): source $(PACKAGE)
	@cd $@; ./configure --prefix=$(PREFIX) \
	--disable-csharp \
	--disable-native-java \
	--disable-java \
	--disable-libasprintf \
	--disable-openmp \
	--without-emacs \
	--without-git \
	--without-cvs
