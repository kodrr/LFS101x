The /bin directory contains executable binaries, essential commands used to boot the system or in single-user mode, and essential commands required by all system users, such as cat, cp, ls, mv, ps, and rm.

/sbin directory is intended for essential binaries related to system administration, such as fsck and ip. To view a list of these programs,

The /proc filesystem contains virtual files (files that exist only in memory) that permit viewing constantly changing kernel data. /proc contains files and directories that mimic kernel structures and configuration information. It does not contain real files, but runtime system information, e.g. system memory, devices mounted, hardware configuration, etc.

The /dev directory contains device nodes, a type of pseudo-file used by most hardware and software devices, except for network devices.

The /var directory contains files that are expected to change in size and content as the system is running (var stands for variable)

The /etc directory is the home for system configuration files. It contains no binary programs, although there are some executable scripts.

The /boot directory contains the few essential files needed to boot the system.

/lib contains libraries (common code shared by applications and needed for them to run) for the essential programs in /bin and /sbin.

The /mnt directory has been used since the early days of UNIX for temporarily mounting filesystems. These can be those on removable media, but more often might be network filesystems, which are not normally mounted.

/opt Optional application software packages
/sys Virtual pseudo-filesystem giving information about the system and the hardware Can be used to alter system parameters and for debugging purposes
/srv Site-specific data served up by the system Seldom used
/tmp Temporary files; on some distributions erased across a reboot and/or may actually be a ramdisk in memory
/usr Multi-user applications, utilities and data
