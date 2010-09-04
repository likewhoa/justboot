#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.65])
AC_INIT([justboot], [0.5.0], [BUG-REPORT-ADDRESS])
AM_INIT_AUTOMAKE([foreign])
AC_CONFIG_SRCDIR([configure.ac])

datdir=${datadir}/justboot
AC_SUBST([datdir])
busyboxdir=${datdir}/busybox
AC_SUBST([busyboxdir])
datetcdir=${datdir}/etc
AC_SUBST([datetcdir])
datconfddir=${datetcdir}/conf.d
AC_SUBST([datconfddir])
portagedir=${datetcdir}/portage
AC_SUBST([portagedir])
ramfsdir=${datdir}/initramfs
AC_SUBST([ramfsdir])
rametcdir=${ramfsdir}/etc
AC_SUBST([rametcdir])
rammoddir=${rametcdir}/modules
AC_SUBST([rammoddir])
kerneldir=${datdir}/kernel
AC_SUBST([kerneldir])
x86dir=${kerneldir}/x86
AC_SUBST([x86dir])
x86_64dir=${kerneldir}/x86_64
AC_SUBST([x86_64dir])

confdir=${sysconfdir}/justboot
AC_SUBST([confdir])
filesdir=${confdir}/files
AC_SUBST([filesdir])

AC_CONFIG_FILES([Makefile
	data/Makefile
	data/busybox/Makefile
	data/etc/Makefile
	data/etc/conf.d/Makefile
	data/etc/portage/Makefile
	data/initramfs/Makefile
	data/initramfs/etc/Makefile
	data/initramfs/etc/modules/Makefile
	data/kernel/Makefile
	data/kernel/x86/Makefile
	data/kernel/x86_64/Makefile
	etc/Makefile
	etc/files/Makefile])
AC_OUTPUT
