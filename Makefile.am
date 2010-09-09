## Process this file with automake to produce Makefile.in

sbin_SCRIPTS = justboot

SUBDIRS = data etc

edit = sed \
	-e "s:[@]VERSION[@]:$(VERSION):g" \
	-e "s:[@]confdir[@]:$(confdir):g" \
	-e "s:[@]datdir[@]:$(datdir):g"

justboot: Makefile
	rm -f $@
	srcdir=; \
	test -f ./$@.in || srcdir=$(srcdir)/; \
	$(edit) $${srcdir}$@.in > $@

justboot: $(srcdir)/justboot.in

CLEANFILES = justboot

EXTRA_DIST = justboot.in
