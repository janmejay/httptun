EXTRA_DIST = \
	client_tun_up.sh \
	server_tun_up.sh

scriptsdir = $(prefix)/libexec/$(PACKAGE)
scripts_DATA = $(EXTRA_DIST)

install-data-hook:
	chmod -R u+x $(prefix)/libexec/$(PACKAGE)
