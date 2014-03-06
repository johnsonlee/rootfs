BUILD_TOOLS = \
	autoconf  \
	automake  \
	bison     \
	gettext   \
	help2man  \
	libtool   \
	m4        \
	pkg-config

all: subdirs

subdirs: $(BUILD_TOOLS)

bison: gettext m4

$(BUILD_TOOLS):
	@for i in $@; do $(MAKE) -C $$i; done

clean:
	@for i in $(BUILD_TOOLS); do $(MAKE) -C $$i $@; done

distclean:
	@for i in $(BUILD_TOOLS); do $(MAKE) -C $$i $@; done

