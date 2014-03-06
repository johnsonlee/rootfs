all: packages tools

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
