PACKAGES = zlib
#   bzip2 \
    expat \
    fontconfig \
    freetype2 \
    gettext \
    glib \
    libffi \
    libgcrypt \
    libgpg-error \
    libiconv \
    libjpeg \
    libpng \
    libxml2 \
    libxslt \
    openssl \
    python27 \
    sqlite3 \
    zlib

all: $(PACKAGES)
	@for i in $^; do $(MAKE) -C $$i; done

clean: $(PACKAGES)
	@for i in $^; do $(MAKE) -C $$i $@; done

distclean: $(PACKAGES)
	@for i in $^; do $(MAKE) -C $$i $@; done

