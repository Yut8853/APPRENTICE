# プロセス・ジョブを管理できる

## 1. プロセス

全ユーザーのプロセスを表示してください。
→
ps aux
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.2 167264 11316 ?        Ss   Sep24   0:02 /sbin/init
root           2  0.0  0.0      0     0 ?        S    Sep24   0:00 [kthreadd]
root           3  0.0  0.0      0     0 ?        I<   Sep24   0:00 [rcu_gp]
root           4  0.0  0.0      0     0 ?        I<   Sep24   0:00 [rcu_par_gp]
root           5  0.0  0.0      0     0 ?        I<   Sep24   0:00 [slub_flushwq
root           6  0.0  0.0      0     0 ?        I<   Sep24   0:00 [netns]
root           8  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kworker/0:0H
root          10  0.0  0.0      0     0 ?        I<   Sep24   0:00 [mm_percpu_wq
root          11  0.0  0.0      0     0 ?        S    Sep24   0:00 [rcu_tasks_ru
root          12  0.0  0.0      0     0 ?        S    Sep24   0:00 [rcu_tasks_tr
root          13  0.0  0.0      0     0 ?        S    Sep24   0:00 [ksoftirqd/0]
root          14  0.0  0.0      0     0 ?        I    Sep24   0:13 [rcu_sched]
root          15  0.0  0.0      0     0 ?        S    Sep24   0:00 [migration/0]
root          16  0.0  0.0      0     0 ?        S    Sep24   0:00 [idle_inject/
root          18  0.0  0.0      0     0 ?        S    Sep24   0:00 [cpuhp/0]
root          19  0.0  0.0      0     0 ?        S    Sep24   0:00 [cpuhp/1]
root          20  0.0  0.0      0     0 ?        S    Sep24   0:00 [idle_inject/
root          21  0.0  0.0      0     0 ?        S    Sep24   0:00 [migration/1]
root          22  0.0  0.0      0     0 ?        S    Sep24   0:00 [ksoftirqd/1]
root          24  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kworker/1:0H
root          25  0.0  0.0      0     0 ?        S    Sep24   0:00 [cpuhp/2]
root          26  0.0  0.0      0     0 ?        S    Sep24   0:00 [idle_inject/
root          27  0.0  0.0      0     0 ?        S    Sep24   0:00 [migration/2]
root          28  0.0  0.0      0     0 ?        S    Sep24   0:00 [ksoftirqd/2]
root          30  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kworker/2:0H
root          31  0.0  0.0      0     0 ?        S    Sep24   0:00 [cpuhp/3]
root          32  0.0  0.0      0     0 ?        S    Sep24   0:00 [idle_inject/
root          33  0.0  0.0      0     0 ?        S    Sep24   0:00 [migration/3]
root          34  0.0  0.0      0     0 ?        S    Sep24   0:00 [ksoftirqd/3]
root          36  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kworker/3:0H
root          37  0.0  0.0      0     0 ?        S    Sep24   0:00 [kdevtmpfs]
root          38  0.0  0.0      0     0 ?        I<   Sep24   0:00 [inet_frag_wq
root          42  0.0  0.0      0     0 ?        S    Sep24   0:00 [kauditd]
root          43  0.0  0.0      0     0 ?        S    Sep24   0:00 [khungtaskd]
root          44  0.0  0.0      0     0 ?        S    Sep24   0:00 [oom_reaper]
root          45  0.0  0.0      0     0 ?        I<   Sep24   0:00 [writeback]
root          46  0.0  0.0      0     0 ?        S    Sep24   0:04 [kcompactd0]
root          47  0.0  0.0      0     0 ?        SN   Sep24   0:00 [ksmd]
root          48  0.0  0.0      0     0 ?        SN   Sep24   0:00 [khugepaged]
root          94  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kintegrityd]
root          95  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kblockd]
root          96  0.0  0.0      0     0 ?        I<   Sep24   0:00 [blkcg_punt_b
root          97  0.0  0.0      0     0 ?        I<   Sep24   0:00 [tpm_dev_wq]
root          98  0.0  0.0      0     0 ?        I<   Sep24   0:00 [ata_sff]
root          99  0.0  0.0      0     0 ?        I<   Sep24   0:00 [md]
root         100  0.0  0.0      0     0 ?        I<   Sep24   0:00 [edac-poller]
root         101  0.0  0.0      0     0 ?        I<   Sep24   0:00 [devfreq_wq]
root         102  0.0  0.0      0     0 ?        S    Sep24   0:00 [watchdogd]
root         104  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kworker/2:1H
root         105  0.0  0.0      0     0 ?        S    Sep24   0:00 [kswapd0]
root         106  0.0  0.0      0     0 ?        S    Sep24   0:00 [ecryptfs-kth
root         108  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kthrotld]
root         109  0.0  0.0      0     0 ?        S    Sep24   0:00 [irq/49-ACPI:
root         110  0.0  0.0      0     0 ?        I<   Sep24   0:00 [acpi_thermal
root         112  0.0  0.0      0     0 ?        I<   Sep24   0:00 [mld]
root         113  0.0  0.0      0     0 ?        I<   Sep24   0:00 [ipv6_addrcon
root         122  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kstrp]
root         125  0.0  0.0      0     0 ?        I<   Sep24   0:00 [zswap-shrink
root         126  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kworker/u9:0
root         130  0.0  0.0      0     0 ?        I<   Sep24   0:00 [cryptd]
root         168  0.0  0.0      0     0 ?        I<   Sep24   0:00 [charger_mana
root         193  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kworker/0:1H
root         219  0.0  0.0      0     0 ?        S    Sep24   0:00 [hwrng]
root         221  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kworker/3:1H
root         233  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kworker/1:1H
root         280  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kdmflush]
root         310  0.0  0.0      0     0 ?        I<   Sep24   0:00 [raid5wq]
root         357  0.0  0.0      0     0 ?        S    Sep24   0:00 [scsi_eh_0]
root         358  0.0  0.0      0     0 ?        I<   Sep24   0:00 [scsi_tmf_0]
root         359  0.0  0.0      0     0 ?        S    Sep24   0:08 [usb-storage]
root         360  0.0  0.0      0     0 ?        I<   Sep24   0:00 [uas]
root         371  0.0  0.0      0     0 ?        S    Sep24   0:00 [jbd2/dm-0-8]
root         372  0.0  0.0      0     0 ?        I<   Sep24   0:00 [ext4-rsv-con
root         449  0.0  0.5  56736 23568 ?        S<s  Sep24   0:00 /lib/systemd/
root         484  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kaluad]
root         488  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kmpath_rdacd
root         491  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kmpathd]
root         492  0.0  0.0      0     0 ?        I<   Sep24   0:00 [kmpath_handl
root         493  0.0  0.6 289664 25668 ?        SLsl Sep24   0:11 /sbin/multipa
root         499  0.0  0.1  26584  6788 ?        Ss   Sep24   0:00 /lib/systemd/
root         642  0.0  0.0      0     0 ?        S    Sep24   0:00 [jbd2/vda2-8]
root         643  0.0  0.0      0     0 ?        I<   Sep24   0:00 [ext4-rsv-con
systemd+     685  0.2  0.0  14992  3788 ?        Ss   Sep24   1:42 /lib/systemd/
systemd+     687  0.0  0.1  88732  6468 ?        Ssl  Sep24   0:00 /lib/systemd/
systemd+     742  0.0  0.1  16396  7716 ?        Ss   Sep24   0:00 /lib/systemd/
systemd+     744  0.0  0.2  25212 11580 ?        Ss   Sep24   0:00 /lib/systemd/
avahi        755  0.0  0.0   8060  3308 ?        Ss   Sep24   0:01 avahi-daemon:
message+     756  0.0  0.1  11480  6372 ?        Ss   Sep24   0:00 @dbus-daemon 
root         757  0.0  0.4 259596 16752 ?        Ssl  Sep24   0:02 /usr/sbin/Net
root         761  0.0  0.0  82104  3272 ?        Ssl  Sep24   0:04 /usr/sbin/irq
root         763  0.0  0.4  39128 19764 ?        Ss   Sep24   0:00 /usr/bin/pyth
root         764  0.0  0.2 240472 10640 ?        Ssl  Sep24   0:00 /usr/libexec/
root         765  0.0  0.1 237324  6588 ?        Ssl  Sep24   0:00 /usr/libexec/
syslog       766  0.0  0.1 222132  4792 ?        Ssl  Sep24   0:00 /usr/sbin/rsy
root         768  0.0  0.7 1466256 28604 ?       Ssl  Sep24   0:04 /usr/lib/snap
root         771  0.0  0.1 237088  6912 ?        Ssl  Sep24   0:01 /usr/libexec/
root         772  0.0  0.1 233740  4632 ?        Ssl  Sep24   0:00 /usr/libexec/
root         773  0.0  0.1  15648  7436 ?        Ss   Sep24   0:00 /lib/systemd/
root         774  0.0  0.2 394032 11728 ?        Ssl  Sep24   0:00 /usr/libexec/
root         775  0.0  0.1  15236  5432 ?        Ss   Sep24   0:00 /sbin/wpa_sup
avahi        779  0.0  0.0   7788   356 ?        S    Sep24   0:00 avahi-daemon:
root         805  0.0  0.2 320780 11396 ?        Ssl  Sep24   0:00 /usr/sbin/Mod
root         812  0.0  0.3  74380 12840 ?        Ss   Sep24   0:00 /usr/sbin/cup
root         838  0.0  0.5 116108 21860 ?        Ssl  Sep24   0:00 /usr/bin/pyth
lp           846  0.0  0.1  16348  5408 ?        S    Sep24   0:00 /usr/lib/cups
root         859  0.0  0.2 173528  9976 ?        Ssl  Sep24   0:00 /usr/sbin/cup
root         865  0.0  0.0   6520  2588 ?        Ss   Sep24   0:00 /usr/sbin/cro
root         873  0.0  0.0   5216   788 ?        Ss+  Sep24   0:00 /sbin/agetty 
kernoops     878  0.0  0.0  12756  1944 ?        Ss   Sep24   0:00 /usr/sbin/ker
kernoops     887  0.0  0.0  12756  1948 ?        Ss   Sep24   0:00 /usr/sbin/ker
root         888  0.0  0.1  15140  7140 ?        Ss   Sep24   0:00 sshd: /usr/sb
root         892  0.0  0.2 238944  8128 ?        Ssl  Sep24   0:00 /usr/sbin/gdm
rtkit       1078  0.0  0.0 153476  1616 ?        SNsl Sep24   0:01 /usr/libexec/
root        1159  0.0  0.1 239456  7732 ?        Ssl  Sep24   0:00 /usr/libexec/
geoclue     1198  0.0  0.2 281036 11672 ?        Ssl  Sep24   0:00 /usr/libexec/
root        1199  0.0  0.4 297128 19232 ?        Ssl  Sep24   0:06 /usr/libexec/
colord      1346  0.0  0.3 243156 12464 ?        Ssl  Sep24   0:00 /usr/libexec/
root        1393  0.0  0.1  86616  4820 ?        Ssl  Sep24   0:05 /usr/sbin/spi
root        1415  0.0  0.2 317428 10432 ?        Sl   Sep24   0:00 gdm-session-w
factory     1423  0.0  0.2  18072  9968 ?        Ss   Sep24   0:01 /lib/systemd/
factory     1424  0.0  0.1 172140  5880 ?        S    Sep24   0:00 (sd-pam)
factory     1430  0.0  0.1  37296  5928 ?        S<sl Sep24   0:00 /usr/bin/pipe
factory     1431  0.0  0.1  20948  5884 ?        Ssl  Sep24   0:00 /usr/bin/pipe
factory     1432  0.0  0.6 1424528 24532 ?       S<sl Sep24   0:00 /usr/bin/puls
factory     1437  0.0  0.1 238032  7352 ?        Sl   Sep24   0:00 /usr/bin/gnom
factory     1438  0.0  0.1  11424  6988 ?        Ss   Sep24   0:01 /usr/bin/dbus
factory     1442  0.0  0.1 237940  7196 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1447  0.0  0.1 381012  5304 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1456  0.0  0.1 159580  5444 tty2     Ssl+ Sep24   0:00 /usr/libexec/
factory     1460  0.0  0.3 222824 13740 tty2     Sl+  Sep24   0:00 /usr/libexec/
factory     1482  0.0  0.6 634316 24788 ?        SNsl Sep24   0:01 /usr/libexec/
factory     1510  0.0  0.0  88920  2616 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1521  0.0  0.2 313468  8484 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1523  0.0  0.3 593032 16008 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1532  0.0  0.1 235128  6332 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1539  0.0  0.1 233812  4980 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1544  0.0  0.1 233936  5904 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1551  0.0  0.9 574604 37512 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1558  0.0  0.1 309772  6996 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1567  0.0  0.1   8924  4212 ?        S    Sep24   0:00 /usr/bin/dbus
factory     1568  0.9 10.3 5455360 413708 ?      Ssl  Sep24   7:32 /usr/bin/gnom
factory     1576  0.0  0.3 338376 13024 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1581  0.0  0.1 312352  6456 ?        Ssl  Sep24   0:05 /usr/libexec/
factory     1609  0.0  0.1 233392  5092 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1611  0.0  0.4 584888 18308 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1620  0.0  0.5 1074192 23476 ?       Ssl  Sep24   0:00 /usr/libexec/
factory     1628  0.0  0.7 916808 28236 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1636  0.0  0.1 156728  5356 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1641  0.0  0.6 746240 26648 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1645  0.0  0.1 386052  7504 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1664  0.0  0.6 2732080 25804 ?       Sl   Sep24   0:00 /usr/bin/gjs 
factory     1665  0.0  0.1 162952  5484 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1676  0.0  0.0   2308   840 ?        Ss   Sep24   0:00 sh -c /usr/bi
factory     1678  0.0  0.1 307892  6048 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1680  0.0  0.6 676512 25516 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1681  0.0  0.3 376056 14568 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1683  0.0  0.2 312796 11480 ?        Sl   Sep24   0:06 /usr/bin/ibus
factory     1684  0.0  0.1 309652  6808 ?        Ssl  Sep24   0:01 /usr/libexec/
factory     1690  0.0  0.5 340424 20492 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1691  0.0  0.6 865156 25028 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1692  0.0  0.6 524864 24660 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1693  0.0  0.2 248040  9988 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1694  0.0  0.1 455504  6116 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1696  0.0  0.1 233644  4668 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1697  0.0  0.2 463908  8864 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1699  0.0  0.1 457580  7312 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1704  0.0  0.2 317564  8252 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1705  0.0  0.5 415084 21080 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1734  0.0  0.1 160820  6636 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1736  0.0  0.6 346768 26764 ?        Sl   Sep24   0:01 /usr/libexec/
factory     1759  0.0  0.1 234656  5860 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1760  0.0  0.6 271460 24340 ?        Ssl  Sep24   0:00 /usr/bin/spic
factory     1773  0.0  0.3 342632 12652 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1791  0.0  1.5 195920 63220 ?        S    Sep24   0:00 /usr/bin/Xway
factory     1798  0.0  0.1 160952  6620 ?        Sl   Sep24   0:02 /usr/libexec/
factory     1817  0.0  0.3 622156 13044 ?        Ssl  Sep24   0:02 /usr/libexec/
factory     1821  0.0  0.1 609144  6528 ?        Ssl  Sep24   0:00 /usr/libexec/
root        1826  0.0  0.0   2212   796 ?        Ss   Sep24   0:00 fusermount3 -
factory     1830  0.0  0.6 662752 27696 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1839  0.0  1.9 520132 79000 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1853  0.0  0.6 2601116 26220 ?       Sl   Sep24   0:00 /usr/bin/gjs 
factory     1898  0.0  0.5 343364 23520 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     1900  0.0  0.5 193616 21984 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1918  0.0  1.4 816036 60032 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1922  0.0  0.1 232152  6400 ?        Sl   Sep24   0:00 /usr/libexec/
factory     1988  0.0  0.1 160360  5940 ?        Ssl  Sep24   0:00 /usr/libexec/
factory     2016  0.0  1.2 555520 51300 ?        Rsl  Sep24   0:26 /usr/libexec/
factory     2034  0.0  0.1   8464  5244 pts/0    Ss   Sep24   0:00 bash
factory     2075  0.0  0.7 494292 30320 ?        Sl   Sep24   0:02 update-notifi
root        8419  0.0  0.0      0     0 ?        I    01:59   0:00 [kworker/2:0-
root        8452  0.0  0.0      0     0 ?        I    02:12   0:00 [kworker/0:2-
root        8512  0.0  0.0      0     0 ?        I    02:12   0:00 [kworker/3:3-
root        8707  0.0  0.0      0     0 ?        I    02:18   0:00 [kworker/1:0-
root        8735  0.0  0.0      0     0 ?        I    02:19   0:00 [kworker/3:2-
root        8736  0.0  0.0      0     0 ?        I    02:19   0:00 [kworker/2:2-
root        8782  0.0  0.0      0     0 ?        I    02:31   0:00 [kworker/u8:0
factory     8809  0.0  1.4 2855568 58364 ?       Sl   02:48   0:00 gjs /usr/shar
root        8834  0.0  0.0      0     0 ?        I    02:48   0:00 [kworker/u8:2
root        8845  0.0  0.0      0     0 ?        I    02:48   0:00 [kworker/0:0-
root        8852  0.0  0.0      0     0 ?        I    02:49   0:00 [kworker/1:1-
root        8880  0.0  0.0      0     0 ?        R    02:52   0:00 [kworker/u8:4
root        8891  0.0  0.0      0     0 ?        I    02:57   0:00 [kworker/0:1-
root        8934  0.0  0.0      0     0 ?        I    02:58   0:00 [kworker/0:3-
factory    11905  0.0  0.0   9420  1652 pts/0    R+   02:59   0:00 ps aux


## 2. バックグラウンド

sleep コマンドを利用して処理を100秒停止する処理を、バックグラウンドで実行してください。
→
sleep 100 g
sleep: invalid time interval \u2018g\u2019
Try 'sleep --help' for more information.
factory@factory:~$ mkdir test
factory@factory:~$ ls
 COPY.md     error.txt    Public              '~root.txt'   superuser
 Desktop     Music        README.md            root.txt     Templates
 Documents   permission   README_SYMBOLIC.md   sample.txt   test
 Downloads   Pictures     result.txt           snap         Videos


## 3. プロセス・ジョブの終了

2でバックグラウンドで実行されている sleep コマンドを終了させてください。
→
sleep 100 &
[1] 11959
factory@factory:~$ jobs
[1]+  Running                 sleep 100 &
factory@factory:~$ kill %1
factory@factory:~$ jobs
[1]+  Terminated              sleep 100
