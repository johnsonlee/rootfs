all: packages

packages: tools
	@$(MAKE) -C $@

tools:
	@$(MAKE) -C $@

clean:
	@$(MAKE) -C tools $@
	@$(MAKE) -C packages $@

distclean:
	@$(MAKE) -C tools $@
	@$(MAKE) -C packages $@

.PHONY: packages tools
