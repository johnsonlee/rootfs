BUILD_TOOLS = \
	autoconf  \
	automake  \
	bison     \
	gettext   \
	help2man  \
	libtool   \
	m4        \
	pkg-config

all: $(BUILD_TOOLS)
	@for i in $^; do $(MAKE) -C $$i; done

bison: gettext m4

clean:
	@for i in $(BUILD_TOOLS); do $(MAKE) -C $$i $@; done

distclean:
	@for i in $(BUILD_TOOLS); do $(MAKE) -C $$i $@; done
