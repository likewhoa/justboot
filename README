JustBOOT(tm) a gentoo livecd generator is in early beta, below are some of the commands that you should run
to help me focus on code and bug fixing. Any suggestions, comments or criticism is appreciated as long
as it's constructive. Hope you enjoy the script and ideas are welcome.

*** YOU MUST RUN ./install prior to running the justboot script ***
*** NOTE that only zen-sources is supported with --kernel flag for now ***

Start by running all of some of the following commands:

justboot --arch=x86_64 --root-passwd="gentoo rocks"
justboot --arch=i686 --volid=gentoo
justboot --arch=x86_64 -ramfs # MAKE SURE YOU HAVE >4GB of RAM
justboot --arch=x86_64 --purge
justboot --arch=x86_64 --root-passwd="gentoo rocks" --volid=gentoo --data-directory=/opt
justboot --arch=x86_64 --make-opts=-j3 --niceness=-5
justboot --arch=i686 --package-manager=pkgcore

FIle locations for extra packages, excluded directories and ramfs mounts are located at
/etc/justboot/files

Per user configuration options for gentoo make.conf can be set in ~/.justboot/arch.conf
where arch is either i386,i486,i586,i686 or x86_64

Thanks for your testing
likewhoa



