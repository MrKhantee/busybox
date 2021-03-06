# BusyBox

Copyright (C) 2015-2018 Anton Skshidlevsky, GPLv2

This application is an BusyBox installer for Android.

[BusyBox](http://busybox.net) combines tiny versions of many common UNIX utilities into a single small executable. It provides replacements for most of the utilities you usually find in GNU fileutils, shellutils, etc. The utilities in BusyBox generally have fewer options than their full-featured GNU cousins; however, the options that are included provide the expected functionality and behave very much like their GNU counterparts. BusyBox provides a fairly complete environment for any small or embedded system.

<a href="https://f-droid.org/packages/ru.meefik.busybox/" target="_blank">
<img src="https://f-droid.org/badge/get-it-on.png" alt="Get it on F-Droid" height="80"/></a>
<a href="https://play.google.com/store/apps/details?id=ru.meefik.busybox" target="_blank">
<img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" alt="Get it on Google Play" height="80"/></a>

Latest BusyBox v1.29.2, supported 370 applets:

	[, [[, acpid, adjtimex, ar, arch, arp, ash, awk, base64, basename,
	bbconfig, beep, blkdiscard, blkid, blockdev, bootchartd, brctl,
	bunzip2, busybox, bzcat, bzip2, cal, cat, chat, chattr, chgrp, chmod,
	chown, chpst, chroot, chrt, chvt, cksum, clear, cmp, comm, conspy, cp,
	cpio, crond, crontab, cryptpw, cttyhack, cut, date, dc, dd, deallocvt,
	depmod, devfsd, devmem, df, dhcprelay, diff, dirname, dmesg, dnsd,
	dnsdomainname, dos2unix, dpkg, dpkg-deb, du, dumpkmap, dumpleases,
	echo, ed, egrep, eject, env, envdir, envuidgid, ether-wake, expand,
	expr, factor, fakeidentd, fallocate, false, fatattr, fbset, fbsplash,
	fdflush, fdformat, fdisk, fgconsole, fgrep, find, findfs, flock, fold,
	free, freeramdisk, fsck, fsck.minix, fsfreeze, fstrim, fsync, ftpd,
	ftpget, ftpput, fuser, getopt, getty, grep, groups, gunzip, gzip, halt,
	hd, hdparm, head, hexdump, hexedit, hostname, httpd, hush, hwclock,
	i2cdetect, i2cdump, i2cget, i2cset, id, ifconfig, ifdown, ifenslave,
	ifplugd, ifup, inetd, init, inotifyd, insmod, install, ionice, iostat,
	ip, ipaddr, ipcalc, iplink, ipneigh, iproute, iprule, iptunnel,
	kbd_mode, kill, killall, killall5, klogd, less, link, linux32, linux64,
	linuxrc, ln, loadkmap, logger, logname, losetup, lpd, lpq, lpr, ls,
	lsattr, lsmod, lsof, lspci, lsscsi, lsusb, lzcat, lzma, lzop, lzopcat,
	makedevs, makemime, man, md5sum, mesg, microcom, mkdir, mkdosfs,
	mke2fs, mkfifo, mkfs.ext2, mkfs.minix, mkfs.reiser, mkfs.vfat, mknod,
	mkpasswd, mkswap, mktemp, modinfo, modprobe, more, mount, mountpoint,
	mpstat, mt, mv, nameif, nbd-client, nc, netstat, nice, nl, nmeter,
	nohup, nproc, nsenter, nslookup, ntpd, nuke, od, openvt, partprobe,
	paste, patch, pgrep, pidof, ping, ping6, pipe_progress, pivot_root,
	pkill, pmap, popmaildir, poweroff, powertop, printenv, printf, ps,
	pscan, pstree, pwd, pwdx, raidautorun, rdate, rdev, readlink,
	readprofile, realpath, reboot, reformime, renice, reset, resize,
	resume, rev, rfkill, rm, rmdir, rmmod, route, rpm, rpm2cpio, rtcwake,
	run-init, run-parts, runsv, runsvdir, rx, script, scriptreplay, sed,
	sendmail, seq, setarch, setconsole, setfattr, setkeycodes, setlogcons,
	setpriv, setserial, setsid, setuidgid, sh, sha1sum, sha256sum, sha3sum,
	sha512sum, showkey, shred, shuf, slattach, sleep, smemcap, softlimit,
	sort, split, start-stop-daemon, stat, strings, stty, sum, sv, svc,
	svlogd, svok, swapoff, swapon, switch_root, sync, sysctl, tac, tail,
	tar, taskset, tc, tcpsvd, tee, telnet, telnetd, test, tftp, tftpd,
	time, timeout, top, touch, tr, traceroute, traceroute6, true, truncate,
	tty, ttysize, tunctl, tune2fs, ubiattach, ubidetach, ubimkvol,
	ubirmvol, ubirsvol, ubiupdatevol, udhcpc, udhcpd, udpsvd, uevent,
	umount, uname, uncompress, unexpand, uniq, unix2dos, unlink, unlzma,
	unlzop, unshare, unxz, unzip, uptime, usleep, uudecode, uuencode,
	vconfig, vi, volname, watch, watchdog, wc, wget, which, whoami, whois,
	xargs, xxd, xz, xzcat, yes, zcat, zcip

**Requirements**:

* Device with architecture ARM, x86 or MIPS
* Android 4.0 (API 14) or later
* Superuser permissions (root)

**Use without root permissions**

To access busybox tools without superuser privileges, perform the following command in Android terminal:

    export PATH=/data/data/ru.meefik.busybox/files/bin:$PATH

**References**:

* [Source code](https://github.com/meefik/busybox)
* [Releases](https://github.com/meefik/busybox/releases)
* [Donations](http://meefik.github.io/donate/)
