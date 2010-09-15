## Process this file with automake to produce Makefile.in

dat_DATA = justboot.globals

edit = sed \
	-e "s:[@]datdir[@]:$(datdir):g"

justboot.globals: Makefile
	rm -f $@
	srcdir=; \
	test -f ./$@.in || srcdir=$(srcdir)/; \
	$(edit) $${srcdir}$@.in > $@

justboot.globals: $(srcdir)/justboot.globals.in

CLEANFILES = justboot.globals

EXTRA_DIST = justboot.globals.in

SUBDIRS = busybox etc initramfs kernel

