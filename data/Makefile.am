## Process this file with automake to produce Makefile.in

dat_DATA = config.globals

edit = sed \
	-e "s:[@]datdir[@]:$(datdir):g"

config.globals: Makefile
	rm -f $@
	srcdir=; \
	test -f ./$@.in || srcdir=$(srcdir)/; \
	$(edit) $${srcdir}$@.in > $@

config.globals: $(srcdir)/config.globals.in

CLEANFILES = config.globals

EXTRA_DIST = config.globals.in

SUBDIRS = busybox etc initramfs kernel

