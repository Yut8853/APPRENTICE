# ディレクトリを操作できる

Linux にログインしてターミナル上で行ってください。

## 1. 現在のディレクトリ

自分が現在いるディレクトリを表示してください。
→
/home/factory

## 2. ルートディレクトリ

現在のディレクトリから、"/" ディレクトリに移動してください。
→
cd /

## 3. ホームディレクトリ

現在のディレクトリから、ホームディレクトリに移動してください。
→
cd ~

## 4. 一つ上のディレクトリ

現在のディレクトリから、一つ上の親ディレクトリに移動してください。
→
cd ..

## 5. ディレクトリの内容

現在のディレクトリの内容を表示してください。
→
/home

## 6. 隠しファイル

現在のディレクトリの隠しファイルを含む全てのファイルとディレクトリを表示してください。
→
.  ..  factory

## 7. 詳細なリスト形式

"/etc" ディレクトリの内容を、詳細なリスト形式で表示してください。

なおわからない場合は、"man ls" コマンドで ls コマンドの詳細を確認することができます。"List files in the long format" といった説明のあるオプションを付けてください。
→
total 1200
drwxr-xr-x 140 root root      12288 Sep 24 01:53 .
drwxr-xr-x  19 root root       4096 Sep 24 01:38 ..
-rw-r--r--   1 root root       3028 Aug 10 00:19 adduser.conf
drwxr-xr-x   3 root root       4096 Sep 24 01:50 alsa
drwxr-xr-x   2 root root       4096 Sep 24 01:53 alternatives
-rw-r--r--   1 root root        335 Mar 23  2022 anacrontab
-rw-r--r--   1 root root        433 Mar 23  2022 apg.conf
drwxr-xr-x   5 root root       4096 Sep 24 01:50 apm
drwxr-xr-x   3 root root       4096 Aug 10 00:31 apparmor
drwxr-xr-x   8 root root       4096 Sep 24 01:53 apparmor.d
drwxr-xr-x   4 root root       4096 Sep 24 01:51 apport
-rw-r--r--   1 root root        769 Feb 22  2022 appstream.conf
drwxr-xr-x   8 root root       4096 Sep 24 01:34 apt
drwxr-xr-x   3 root root       4096 Sep 24 01:52 avahi
-rw-r--r--   1 root root       2319 Jan  6  2022 bash.bashrc
-rw-r--r--   1 root root         45 Nov 11  2021 bash_completion
drwxr-xr-x   2 root root       4096 Aug 10 00:32 bash_completion.d
-rw-r--r--   1 root root        367 Dec 16  2020 bindresvport.blacklist
drwxr-xr-x   2 root root       4096 Mar 20  2023 binfmt.d
drwxr-xr-x   2 root root       4096 Sep 24 01:51 bluetooth
-rw-r-----   1 root root         33 Sep 24 01:52 brlapi.key
drwxr-xr-x   7 root root       4096 Sep 24 01:51 brltty
-rw-r--r--   1 root root      29219 Jun 28  2022 brltty.conf
drwxr-xr-x   2 root root       4096 Aug 10 00:32 byobu
drwxr-xr-x   3 root root       4096 Aug 10 00:29 ca-certificates
-rw-r--r--   1 root root       5892 Aug 10 00:29 ca-certificates.conf
drwxr-s---   2 root dip        4096 Sep 24 01:51 chatscripts
drwxr-xr-x   5 root root       4096 Sep 24 01:37 cloud
drwxr-xr-x   2 root root       4096 Sep 24 01:35 console-setup
drwxr-xr-x   2 root root       4096 Sep 24 01:52 cracklib
drwxr-xr-x   2 root root       4096 Sep 24 01:51 cron.d
drwxr-xr-x   2 root root       4096 Sep 24 01:52 cron.daily
drwxr-xr-x   2 root root       4096 Aug 10 00:31 cron.hourly
drwxr-xr-x   2 root root       4096 Sep 24 01:51 cron.monthly
-rw-r--r--   1 root root       1136 Mar 23  2022 crontab
drwxr-xr-x   2 root root       4096 Sep 24 01:51 cron.weekly
drwxr-xr-x   2 root root       4096 Aug 10 00:29 cryptsetup-initramfs
-rw-r--r--   1 root root         54 Aug 10 00:29 crypttab
drwxr-xr-x   5 root lp         4096 Sep 24 09:09 cups
drwxr-xr-x   2 root root       4096 Sep 24 01:52 cupshelpers
drwxr-xr-x   4 root root       4096 Aug 10 00:29 dbus-1
drwxr-xr-x   4 root root       4096 Sep 24 01:51 dconf
-rw-r--r--   1 root root       2969 Feb 20  2022 debconf.conf
-rw-r--r--   1 root root         13 Aug 22  2021 debian_version
drwxr-xr-x   3 root root       4096 Sep 24 01:52 default
-rw-r--r--   1 root root        604 Sep 15  2018 deluser.conf
drwxr-xr-x   2 root root       4096 Aug 10 00:31 depmod.d
drwxr-xr-x   4 root root       4096 Aug 10 00:31 dhcp
drwxr-xr-x   2 root root       4096 Sep 24 01:53 dictionaries-common
drwxr-xr-x   4 root root       4096 Aug 10 00:30 dpkg
-rw-r--r--   1 root root        685 Jan  8  2022 e2scrub.conf
drwxr-xr-x   3 root root       4096 Sep 24 01:50 emacs
-rw-r--r--   1 root root        106 Aug 10 00:19 environment
drwxr-xr-x   2 root root       4096 Sep 24 01:52 environment.d
-rw-r--r--   1 root root       1816 Dec 27  2019 ethertypes
drwxr-xr-x   3 root root       4096 Sep 24 01:50 firefox
drwxr-xr-x   4 root root       4096 Sep 24 01:52 fonts
-rw-r--r--   1 root root         20 Feb 24  2022 fprintd.conf
-rw-r--r--   1 root root        769 Sep 24 01:36 fstab
-rw-r--r--   1 root root        694 Mar 23  2022 fuse.conf
drwxr-xr-x   3 root root       4096 Aug 10 00:32 fwupd
-rw-r--r--   1 root root       2584 Feb  3  2022 gai.conf
drwxr-xr-x   3 root root       4096 Sep 24 01:52 gdb
drwxr-xr-x   8 root root       4096 Sep 24 01:53 gdm3
drwxr-xr-x   2 root root       4096 Sep 24 01:52 geoclue
drwxr-xr-x   4 root root       4096 Sep 24 01:50 ghostscript
drwxr-xr-x   3 root root       4096 Sep 24 01:50 glvnd
drwxr-xr-x   2 root root       4096 Sep 24 01:51 gnome
drwxr-xr-x   2 root root       4096 Aug 10 00:31 groff
-rw-r--r--   1 root root       1085 Sep 24 01:53 group
-rw-r--r--   1 root root       1074 Sep 24 01:53 group-
drwxr-xr-x   2 root root       4096 Sep 24 01:35 grub.d
-rw-r-----   1 root shadow      901 Sep 24 01:53 gshadow
-rw-r-----   1 root shadow      893 Sep 24 01:53 gshadow-
drwxr-xr-x   3 root root       4096 Feb 21  2022 gss
drwxr-xr-x   2 root root       4096 Sep 24 01:52 gtk-2.0
drwxr-xr-x   2 root root       4096 Sep 24 01:52 gtk-3.0
-rw-r--r--   1 root root       4436 Dec 15  2020 hdparm.conf
-rw-r--r--   1 root root         92 Oct 15  2021 host.conf
-rw-r--r--   1 root adm           8 Sep 24 01:37 hostname
-rw-r--r--   1 root adm         222 Sep 24 01:37 hosts
-rw-r--r--   1 root root        411 Aug 10 00:29 hosts.allow
-rw-r--r--   1 root root        711 Aug 10 00:29 hosts.deny
drwxr-xr-x   2 root root       4096 Sep 24 01:53 hp
drwxr-xr-x   3 root root       4096 Sep 24 01:51 ifplugd
drwxr-xr-x   2 root root       4096 Sep 24 01:52 init
drwxr-xr-x   2 root root       4096 Sep 24 01:53 init.d
drwxr-xr-x   5 root root       4096 Aug 10 00:31 initramfs-tools
-rw-r--r--   1 root root       1748 Jan  6  2022 inputrc
drwxr-xr-x   2 root root       4096 Sep 24 01:53 insserv.conf.d
drwxr-xr-x   2 root root       4096 Sep 24 01:52 ipp-usb
drwxr-xr-x   4 root root       4096 Aug 10 00:31 iproute2
drwxr-xr-x   2 root root       4096 Aug 10 00:31 iscsi
-rw-r--r--   1 root root         26 Aug  2 13:14 issue
-rw-r--r--   1 root root         19 Aug  2 13:14 issue.net
drwxr-xr-x   5 root root       4096 Aug 10 00:29 kernel
-rw-r--r--   1 root root       1308 Mar 24  2022 kerneloops.conf
drwxrwxr-x   2 root landscape  4096 Mar 30  2022 landscape
drwxr-xr-x   2 root root       4096 Aug 10 00:31 ldap
-rw-r--r--   1 root root      60519 Sep 24 01:53 ld.so.cache
-rw-r--r--   1 root root         34 Dec 16  2020 ld.so.conf
drwxr-xr-x   2 root root       4096 Sep 24 01:47 ld.so.conf.d
-rw-r--r--   1 root root        267 Oct 15  2021 legal
-rw-r--r--   1 root root         27 Mar 13  2022 libao.conf
-rw-r--r--   1 root root        191 Mar 17  2022 libaudit.conf
drwxr-xr-x   3 root root       4096 Aug 10 00:32 libblockdev
drwxr-xr-x   2 root root       4096 Aug 10 00:32 libnl-3
drwxr-xr-x   2 root root       4096 Mar 24  2022 libpaper.d
drwxr-xr-x   3 root root       4096 Sep 24 01:52 libreoffice
-rw-r--r--   1 root root       2996 Jul  6  2022 locale.alias
-rw-r--r--   1 root root       9456 Sep 24 01:40 locale.gen
lrwxrwxrwx   1 root root         27 Aug 10 00:29 localtime -> /usr/share/zoneinfo/Etc/UTC
drwxr-xr-x   5 root root       4096 Sep 24 01:50 logcheck
-rw-r--r--   1 root root      10734 Nov 11  2021 login.defs
-rw-r--r--   1 root root        592 May 25  2022 logrotate.conf
drwxr-xr-x   2 root root       4096 Sep 24 01:53 logrotate.d
-rw-r--r--   1 root root        104 Aug  2 13:13 lsb-release
drwxr-xr-x   3 root root       4096 Aug 10 00:31 lvm
-r--r--r--   1 root root         33 Sep 24 01:35 machine-id
-rw-r--r--   1 root root        111 Mar 24  2022 magic
-rw-r--r--   1 root root        111 Mar 24  2022 magic.mime
-rw-r--r--   1 root root      36929 Sep 24 01:52 mailcap
-rw-r--r--   1 root root        449 Dec 10  2021 mailcap.order
-rw-r--r--   1 root root       5217 Mar 17  2022 manpath.config
drwxr-xr-x   2 root root       4096 Aug 10 00:33 mdadm
-rw-r--r--   1 root root      72029 Mar 21  2022 mime.types
-rw-r--r--   1 root root        744 Jan  8  2022 mke2fs.conf
drwxr-xr-x   4 root root       4096 Aug 10 00:32 ModemManager
drwxr-xr-x   2 root root       4096 Sep 24 01:52 modprobe.d
-rw-r--r--   1 root root        195 Aug 10 00:29 modules
drwxr-xr-x   2 root root       4096 Sep 24 01:47 modules-load.d
lrwxrwxrwx   1 root root         19 Aug 10 00:29 mtab -> ../proc/self/mounts
drwx------   2 root root       4096 Sep 24 01:40 multipath
-rw-r--r--   1 root root         41 Oct 28  2022 multipath.conf
-rw-r--r--   1 root root      11204 Feb  9  2022 nanorc
drwxr-xr-x   6 root root       4096 Aug 10 00:31 needrestart
-rw-r--r--   1 root root        767 Mar 24  2022 netconfig
drwxr-xr-x   2 root root       4096 Sep 24 01:35 netplan
drwxr-xr-x   6 root root       4096 Sep 24 01:51 network
drwxr-xr-x   8 root root       4096 Aug 10 00:29 networkd-dispatcher
drwxr-xr-x   7 root root       4096 Sep 24 01:52 NetworkManager
-rw-r--r--   1 root root         91 Oct 15  2021 networks
drwxr-xr-x   2 root root       4096 Aug 10 00:31 newt
-rwxr-xr-x   1 root root        228 Mar 23  2022 nftables.conf
-rw-r--r--   1 root root        582 Sep 24 01:52 nsswitch.conf
drwxr-xr-x   4 root root       4096 Sep 24 01:52 openvpn
drwxr-xr-x   2 root root       4096 Aug 10 00:18 opt
lrwxrwxrwx   1 root root         21 Aug  2 13:14 os-release -> ../usr/lib/os-release
-rw-r--r--   1 root root       6920 Aug 17  2020 overlayroot.conf
drwxr-xr-x   2 root root       4096 Aug 10 00:29 PackageKit
-rw-r--r--   1 root root        552 Aug 12  2020 pam.conf
drwxr-xr-x   2 root root       4096 Sep 24 01:53 pam.d
-rw-r--r--   1 root root          7 Sep 24 01:51 papersize
-rw-r--r--   1 root root       3095 Sep 24 01:53 passwd
-rw-r--r--   1 root root       3074 Sep 24 01:53 passwd-
drwxr-xr-x   2 root root       4096 Sep 24 01:51 pcmcia
drwxr-xr-x   3 root root       4096 Aug 10 00:29 perl
drwxr-xr-x   4 root root       4096 Aug 10 00:32 pki
drwxr-xr-x   3 root root       4096 Aug 10 00:29 pm
-rw-r--r--   1 root root       7649 Sep 24 01:52 pnm2ppa.conf
drwxr-xr-x   4 root root       4096 Aug 10 00:29 polkit-1
drwxr-xr-x   2 root root       4096 Sep 24 01:36 pollinate
drwxr-xr-x   8 root dip        4096 Sep 24 01:52 ppp
-rw-r--r--   1 root root        582 Oct 15  2021 profile
drwxr-xr-x   2 root root       4096 Sep 24 01:52 profile.d
-rw-r--r--   1 root root       2932 Apr  1  2013 protocols
drwxr-xr-x   4 root root       4096 Sep 24 01:53 pulse
-rw-------   1 root root          0 Aug 10 00:19 .pwd.lock
drwxr-xr-x   2 root root       4096 Aug 10 00:29 python3
drwxr-xr-x   2 root root       4096 Aug 10 00:29 python3.10
drwxr-xr-x   2 root root       4096 Sep 24 01:53 rc0.d
drwxr-xr-x   2 root root       4096 Sep 24 01:53 rc1.d
drwxr-xr-x   2 root root       4096 Sep 24 01:53 rc2.d
drwxr-xr-x   2 root root       4096 Sep 24 01:53 rc3.d
drwxr-xr-x   2 root root       4096 Sep 24 01:53 rc4.d
drwxr-xr-x   2 root root       4096 Sep 24 01:53 rc5.d
drwxr-xr-x   2 root root       4096 Sep 24 01:53 rc6.d
drwxr-xr-x   2 root root       4096 Sep 24 01:52 rcS.d
lrwxrwxrwx   1 root root         39 Aug 10 00:29 resolv.conf -> ../run/systemd/resolve/stub-resolv.conf
lrwxrwxrwx   1 root root         13 Feb 15  2023 rmt -> /usr/sbin/rmt
-rw-r--r--   1 root root        887 Apr  1  2013 rpc
-rw-r--r--   1 root root       1382 Dec 23  2021 rsyslog.conf
drwxr-xr-x   2 root root       4096 Aug 10 00:31 rsyslog.d
-rw-r--r--   1 root root       5620 Jan  9  2022 rygel.conf
drwxr-xr-x   3 root root       4096 Sep 24 01:52 sane.d
-rw-r--r--   1 root root       3663 Jun 20  2016 screenrc
drwxr-xr-x   4 root root       4096 Sep 24 01:51 security
drwxr-xr-x   2 root root       4096 Aug 10 00:30 selinux
-rw-r--r--   1 root root      10593 Mar 31  2022 sensors3.conf
drwxr-xr-x   2 root root       4096 Sep 24 01:51 sensors.d
-rw-r--r--   1 root root      12813 Mar 27  2021 services
drwxr-xr-x   3 root root       4096 Sep 24 01:53 sgml
-rw-r-----   1 root shadow     1605 Sep 24 01:53 shadow
-rw-r-----   1 root shadow     1605 Sep 24 01:53 shadow-
-rw-r--r--   1 root root        158 Aug 10 00:32 shells
drwxr-xr-x   2 root root       4096 Aug 10 00:30 skel
drwxr-xr-x   2 root root       4096 Sep 24 01:51 snmp
drwxr-xr-x   6 root root       4096 Aug 10 00:32 sos
drwxr-xr-x   4 root root       4096 Sep 24 01:52 speech-dispatcher
drwxr-xr-x   4 root root       4096 Sep 24 01:40 ssh
drwxr-xr-x   4 root root       4096 Aug 10 00:31 ssl
drwx--x--x   3 root root       4096 Sep 24 01:51 sssd
-rw-r--r--   1 root root         21 Sep 24 01:40 subgid
-rw-r--r--   1 root root          0 Aug 10 00:19 subgid-
-rw-r--r--   1 root root         21 Sep 24 01:40 subuid
-rw-r--r--   1 root root          0 Aug 10 00:19 subuid-
-rw-r--r--   1 root root       4573 Apr  3 18:00 sudo.conf
-r--r-----   1 root root       1671 Aug  3  2022 sudoers
drwxr-xr-x   2 root root       4096 Aug 10 00:31 sudoers.d
-rw-r--r--   1 root root       9390 Apr  3 18:00 sudo_logsrvd.conf
-rw-r--r--   1 root root       2355 Feb 25  2022 sysctl.conf
drwxr-xr-x   2 root root       4096 Sep 24 01:47 sysctl.d
drwxr-xr-x   5 root root       4096 Sep 24 01:52 systemd
drwxr-xr-x   2 root root       4096 Aug 10 00:28 terminfo
drwxr-xr-x   2 root root       4096 Sep 24 01:52 thunderbird
-rw-r--r--   1 root root          8 Aug 10 00:29 timezone
drwxr-xr-x   2 root root       4096 Aug 10 00:32 tmpfiles.d
drwxr-xr-x   2 root root       4096 Aug 10 00:31 ubuntu-advantage
-rw-r--r--   1 root root       1260 Jun 16  2020 ucf.conf
drwxr-xr-x   4 root root       4096 Aug 10 00:31 udev
drwxr-xr-x   2 root root       4096 Aug 10 00:32 udisks2
drwxr-xr-x   3 root root       4096 Aug 10 00:31 ufw
drwxr-xr-x   3 root root       4096 Aug 10 00:31 update-manager
drwxr-xr-x   2 root root       4096 Aug 10 00:32 update-motd.d
drwxr-xr-x   2 root root       4096 Feb 28  2023 update-notifier
drwxr-xr-x   2 root root       4096 Sep 24 01:52 UPower
-rw-r--r--   1 root root       1523 Mar 25  2022 usb_modeswitch.conf
drwxr-xr-x   2 root root       4096 Sep  6  2021 usb_modeswitch.d
drwxr-xr-x   2 root root       4096 Sep 24 01:38 vim
drwxr-xr-x   4 root root       4096 Sep 24 01:37 vmware-tools
lrwxrwxrwx   1 root root         23 Aug 10 00:29 vtrgb -> /etc/alternatives/vtrgb
drwxr-xr-x   5 root root       4096 Sep 24 01:51 vulkan
-rw-r--r--   1 root root       4942 Jan 24  2022 wgetrc
drwxr-xr-x   2 root root       4096 Sep 24 01:52 wpa_supplicant
drwxr-xr-x  12 root root       4096 Sep 24 01:53 X11
-rw-r--r--   1 root root        681 Mar 23  2022 xattr.conf
drwxr-xr-x   6 root root       4096 Sep 24 01:51 xdg
drwxr-xr-x   2 root root       4096 Sep 24 01:53 xml
-rw-r--r--   1 root root        460 Dec  8  2021 zsh_command_not_found


## 8. ディレクトリの作成

ホームディレクトリに移動し、"projects" という名前のディレクトリを作成してください。
→
mkdir projects

## 9. ディレクトリの削除

作成した "projects" ディレクトリを削除してください。
→
rmdir projects