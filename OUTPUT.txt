1.)Find the Processes running on a linux machine?
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.5 102376 11800 ?        Ss   14:42   0:00 /sbin/init maybe-ubiquity
root           2  0.0  0.0      0     0 ?        S    14:42   0:00 [kthreadd]
root           3  0.0  0.0      0     0 ?        I<   14:42   0:00 [rcu_gp]
root           4  0.0  0.0      0     0 ?        I<   14:42   0:00 [rcu_par_gp]
root           6  0.0  0.0      0     0 ?        I<   14:42   0:00 [kworker/0:0H-kblockd]
root           7  0.0  0.0      0     0 ?        I    14:42   0:00 [kworker/0:1-events]
root           9  0.0  0.0      0     0 ?        I<   14:42   0:00 [mm_percpu_wq]
root          10  0.0  0.0      0     0 ?        S    14:42   0:00 [ksoftirqd/0]
root          11  0.0  0.0      0     0 ?        I    14:42   0:00 [rcu_sched]
root          12  0.0  0.0      0     0 ?        S    14:42   0:00 [migration/0]
root          13  0.0  0.0      0     0 ?        S    14:42   0:00 [idle_inject/0]
root          14  0.0  0.0      0     0 ?        S    14:42   0:00 [cpuhp/0]
root          15  0.0  0.0      0     0 ?        S    14:42   0:00 [cpuhp/1]
root          16  0.0  0.0      0     0 ?        S    14:42   0:00 [idle_inject/1]
root          17  0.0  0.0      0     0 ?        S    14:42   0:00 [migration/1]
root          18  0.0  0.0      0     0 ?        S    14:42   0:00 [ksoftirqd/1]
root          20  0.0  0.0      0     0 ?        I<   14:42   0:00 [kworker/1:0H-kblockd]
root          21  0.0  0.0      0     0 ?        S    14:42   0:00 [kdevtmpfs]
root          22  0.0  0.0      0     0 ?        I<   14:42   0:00 [netns]
root          23  0.0  0.0      0     0 ?        S    14:42   0:00 [rcu_tasks_kthre]
root          24  0.0  0.0      0     0 ?        S    14:42   0:00 [kauditd]
root          25  0.0  0.0      0     0 ?        S    14:42   0:00 [khungtaskd]
root          26  0.0  0.0      0     0 ?        S    14:42   0:00 [oom_reaper]
root          27  0.0  0.0      0     0 ?        I<   14:42   0:00 [writeback]
root          28  0.0  0.0      0     0 ?        S    14:42   0:00 [kcompactd0]
root          29  0.0  0.0      0     0 ?        SN   14:42   0:00 [ksmd]
root          30  0.0  0.0      0     0 ?        SN   14:42   0:00 [khugepaged]
root          34  0.0  0.0      0     0 ?        I    14:42   0:00 [kworker/1:1-events]
root          77  0.0  0.0      0     0 ?        I<   14:42   0:00 [kintegrityd]
root          78  0.0  0.0      0     0 ?        I<   14:42   0:00 [kblockd]
root          79  0.0  0.0      0     0 ?        I<   14:42   0:00 [blkcg_punt_bio]
root          80  0.0  0.0      0     0 ?        I<   14:42   0:00 [tpm_dev_wq]
root          81  0.0  0.0      0     0 ?        I<   14:42   0:00 [ata_sff]
root          82  0.0  0.0      0     0 ?        I<   14:42   0:00 [md]
root          83  0.0  0.0      0     0 ?        I<   14:42   0:00 [edac-poller]
root          84  0.0  0.0      0     0 ?        I<   14:42   0:00 [devfreq_wq]
root          85  0.0  0.0      0     0 ?        S    14:42   0:00 [watchdogd]
root          88  0.0  0.0      0     0 ?        S    14:42   0:00 [kswapd0]
root          89  0.0  0.0      0     0 ?        S    14:42   0:00 [ecryptfs-kthrea]
root          91  0.0  0.0      0     0 ?        I<   14:42   0:00 [kthrotld]
root          92  0.0  0.0      0     0 ?        I<   14:42   0:00 [acpi_thermal_pm]
root          93  0.0  0.0      0     0 ?        S    14:42   0:00 [scsi_eh_0]
root          94  0.0  0.0      0     0 ?        I<   14:42   0:00 [scsi_tmf_0]
root          95  0.0  0.0      0     0 ?        S    14:42   0:00 [scsi_eh_1]
root          96  0.0  0.0      0     0 ?        I<   14:42   0:00 [scsi_tmf_1]
root          98  0.0  0.0      0     0 ?        I<   14:42   0:00 [vfio-irqfd-clea]
root         100  0.0  0.0      0     0 ?        I<   14:42   0:00 [ipv6_addrconf]
root         109  0.0  0.0      0     0 ?        I<   14:42   0:00 [kstrp]
root         112  0.0  0.0      0     0 ?        I<   14:42   0:00 [kworker/u5:0]
root         125  0.0  0.0      0     0 ?        I<   14:42   0:00 [charger_manager]
root         166  0.0  0.0      0     0 ?        S    14:42   0:00 [scsi_eh_2]
root         168  0.0  0.0      0     0 ?        I<   14:42   0:00 [scsi_tmf_2]
root         169  0.0  0.0      0     0 ?        S    14:42   0:00 [scsi_eh_3]
root         170  0.0  0.0      0     0 ?        I<   14:42   0:00 [scsi_tmf_3]
root         172  0.0  0.0      0     0 ?        S    14:42   0:00 [scsi_eh_4]
root         173  0.0  0.0      0     0 ?        I<   14:42   0:00 [cryptd]
root         174  0.0  0.0      0     0 ?        I<   14:42   0:00 [scsi_tmf_4]
root         177  0.0  0.0      0     0 ?        S    14:42   0:00 [scsi_eh_5]
root         181  0.0  0.0      0     0 ?        I<   14:42   0:00 [scsi_tmf_5]
root         207  0.0  0.0      0     0 ?        S    14:42   0:00 [irq/18-vmwgfx]
root         214  0.0  0.0      0     0 ?        I    14:42   0:00 [kworker/1:2-events]
root         216  0.0  0.0      0     0 ?        I<   14:42   0:00 [ttm_swap]
root         217  0.0  0.0      0     0 ?        I<   14:42   0:00 [kworker/0:1H-kblockd]
root         218  0.0  0.0      0     0 ?        I<   14:42   0:00 [kworker/1:1H-kblockd]
root         243  0.0  0.0      0     0 ?        I<   14:42   0:00 [kdmflush]
root         255  0.0  0.0      0     0 ?        I<   14:42   0:00 [kdmflush]
root         281  0.0  0.0      0     0 ?        I<   14:42   0:00 [raid5wq]
root         321  0.0  0.0      0     0 ?        S    14:42   0:00 [jbd2/dm-1-8]
root         322  0.0  0.0      0     0 ?        I<   14:42   0:00 [ext4-rsv-conver]
root         393  0.0  0.7  51688 14392 ?        S<s  14:42   0:00 /lib/systemd/systemd-journald
root         424  0.0  0.2  21248  5288 ?        Ss   14:42   0:00 /lib/systemd/systemd-udevd
root         443  0.0  0.0      0     0 ?        I<   14:42   0:00 [iprt-VBoxWQueue]
root         657  0.0  0.0      0     0 ?        I<   14:42   0:00 [kaluad]
root         658  0.0  0.0      0     0 ?        I<   14:42   0:00 [kmpath_rdacd]
root         659  0.0  0.0      0     0 ?        I<   14:42   0:00 [kmpathd]
root         660  0.0  0.0      0     0 ?        I<   14:42   0:00 [kmpath_handlerd]
root         661  0.0  0.8 280328 18132 ?        SLsl 14:42   0:00 /sbin/multipathd -d -s
root         673  0.0  0.0      0     0 ?        S<   14:42   0:00 [loop0]
root         677  0.0  0.0      0     0 ?        S    14:42   0:00 [jbd2/sda2-8]
root         678  0.0  0.0      0     0 ?        I<   14:42   0:00 [ext4-rsv-conver]
root         679  0.0  0.0      0     0 ?        S<   14:42   0:00 [loop1]
root         680  0.0  0.0      0     0 ?        I<   14:42   0:00 [xfsalloc]
root         681  0.0  0.0      0     0 ?        I<   14:42   0:00 [xfs_mru_cache]
root         682  0.0  0.0      0     0 ?        I<   14:42   0:00 [xfs-buf/dm-0]
root         683  0.0  0.0      0     0 ?        I<   14:42   0:00 [xfs-conv/dm-0]
root         684  0.0  0.0      0     0 ?        I<   14:42   0:00 [xfs-cil/dm-0]
root         685  0.0  0.0      0     0 ?        S<   14:42   0:00 [loop2]
root         686  0.0  0.0      0     0 ?        S<   14:42   0:00 [loop3]
root         687  0.0  0.0      0     0 ?        I<   14:42   0:00 [xfs-reclaim/dm-]
root         688  0.0  0.0      0     0 ?        I<   14:42   0:00 [xfs-eofblocks/d]
root         689  0.0  0.0      0     0 ?        I<   14:42   0:00 [xfs-log/dm-0]
root         690  0.0  0.0      0     0 ?        S    14:42   0:00 [xfsaild/dm-0]
root         691  0.0  0.0      0     0 ?        S<   14:42   0:00 [loop4]
systemd+     707  0.0  0.3  90424  6320 ?        Ssl  14:42   0:00 /lib/systemd/systemd-timesyncd
systemd+     747  0.0  0.3  26792  7772 ?        Ss   14:42   0:00 /lib/systemd/systemd-networkd
systemd+     749  0.0  0.6  24092 12280 ?        Ss   14:42   0:00 /lib/systemd/systemd-resolved
root         761  0.0  0.4 239288  9348 ?        Ssl  14:42   0:00 /usr/lib/accountsservice/accounts-daemon
root         767  0.0  0.1   6812  2916 ?        Ss   14:42   0:00 /usr/sbin/cron -f
message+     771  0.0  0.2   7640  4592 ?        Ss   14:42   0:00 /usr/bin/dbus-daemon --system --address=systemd: --nofork --nopidfile --systemd-activation --syslog-only
root         784  0.0  0.1  81828  3588 ?        Ssl  14:42   0:00 /usr/sbin/irqbalance --foreground
root         785  0.0  0.8  29068 18152 ?        Ss   14:42   0:00 /usr/bin/python3 /usr/bin/networkd-dispatcher --run-startup-triggers
syslog       789  0.0  0.2 224348  4868 ?        Ssl  14:42   0:00 /usr/sbin/rsyslogd -n -iNONE
root         793  0.0  1.2 775520 26020 ?        Ssl  14:42   0:00 /usr/lib/snapd/snapd
root         794  0.0  0.3  16844  8088 ?        Ss   14:42   0:00 /lib/systemd/systemd-logind
daemon       797  0.0  0.1   3792  2168 ?        Ss   14:42   0:00 /usr/sbin/atd -f
root         822  0.0  0.2   6520  4472 ?        Ss   14:42   0:00 /usr/sbin/apache2 -k start
www-data     823  0.0  0.2 1211408 4360 ?        Sl   14:42   0:00 /usr/sbin/apache2 -k start
www-data     824  0.0  0.2 1211408 4360 ?        Sl   14:42   0:00 /usr/sbin/apache2 -k start
root         883  0.0  0.1   5988  3904 tty1     Ss   14:42   0:00 /bin/login -p --
root         895  0.0  1.0 107884 20932 ?        Ssl  14:42   0:00 /usr/bin/python3 /usr/share/unattended-upgrades/unattended-upgrade-shutdown --wait-for-signal
root         896  0.0  0.4 236308  9000 ?        Ssl  14:42   0:00 /usr/lib/policykit-1/polkitd --no-debug
rohit       1135  0.0  0.4  18704  9888 ?        Ss   14:43   0:00 /lib/systemd/systemd --user
rohit       1140  0.0  0.1 103600  3668 ?        S    14:43   0:00 (sd-pam)
rohit       1145  0.0  0.2   8396  5448 tty1     S    14:43   0:00 -bash
root        1163  0.0  0.0      0     0 ?        I    15:24   0:00 [kworker/u4:1-events_unbound]
root        1166  0.0  0.0      0     0 ?        I    15:24   0:00 [kworker/0:2-events]
root        1318  0.0  0.0      0     0 ?        I    15:39   0:00 [kworker/u4:2-events_power_efficient]
rohit       1328  0.0  0.1   8892  3336 tty1     R+   15:45   0:00 ps aux

2.)Find the user currently logged in ?
rohit    tty1         2021-03-06 14:43

3.)Find the uptime of the machine ?
16:01:41 up  1:19,  1 user,  load average: 0.00, 0.00, 0.00

4.)Find the ram usage ? 
              total        used        free      shared  buff/cache   available
Mem:          1.9Gi       145Mi       1.5Gi       1.0Mi       347Mi       1.6Gi
Swap:         1.7Gi          0B       1.7Gi

5.)Find the disk usage ?
4.0K	/home/rohit/.cache
8.0K	/home/rohit/task/.git/refs/remotes/origin
12K	/home/rohit/task/.git/refs/remotes
8.0K	/home/rohit/task/.git/refs/heads
4.0K	/home/rohit/task/.git/refs/tags
28K	/home/rohit/task/.git/refs
8.0K	/home/rohit/task/.git/info
8.0K	/home/rohit/task/.git/objects/9f
8.0K	/home/rohit/task/.git/objects/76
8.0K	/home/rohit/task/.git/objects/74
8.0K	/home/rohit/task/.git/objects/1d
4.0K	/home/rohit/task/.git/objects/info
8.0K	/home/rohit/task/.git/objects/0d
4.0K	/home/rohit/task/.git/objects/pack
8.0K	/home/rohit/task/.git/objects/84
8.0K	/home/rohit/task/.git/objects/e4
8.0K	/home/rohit/task/.git/objects/2f
8.0K	/home/rohit/task/.git/objects/80
8.0K	/home/rohit/task/.git/objects/51
8.0K	/home/rohit/task/.git/objects/18
8.0K	/home/rohit/task/.git/objects/8e
108K	/home/rohit/task/.git/objects
8.0K	/home/rohit/task/.git/logs/refs/remotes/origin
12K	/home/rohit/task/.git/logs/refs/remotes
8.0K	/home/rohit/task/.git/logs/refs/heads
24K	/home/rohit/task/.git/logs/refs
32K	/home/rohit/task/.git/logs
56K	/home/rohit/task/.git/hooks
4.0K	/home/rohit/task/.git/branches
260K	/home/rohit/task/.git
276K	/home/rohit/task
4.0K	/home/rohit/.local/share/nano
8.0K	/home/rohit/.local/share
12K	/home/rohit/.local
316K	/home/rohit

6)Find the inode usage?
Filesystem                          Inodes IUsed    IFree IUse% Mounted on
udev                                243426   528   242898    1% /dev
tmpfs                               254410   813   253597    1% /run
/dev/mapper/ubuntu--vg-ubuntu--lv   589824 77875   511949   14% /
tmpfs                               254410     4   254406    1% /dev/shm
tmpfs                               254410     4   254406    1% /run/lock
tmpfs                               254410    18   254392    1% /sys/fs/cgroup
/dev/loop0                           10809 10809        0  100% /snap/core18/1944
/dev/sda2                            65536   312    65224    1% /boot
/dev/loop1                             474   474        0  100% /snap/snapd/11107
/dev/mapper/vggroup-new--disk     15722496     3 15722493    1% /data
/dev/loop2                           10817 10817        0  100% /snap/core18/1988
/dev/loop3                            1578  1578        0  100% /snap/lxd/19188
/dev/loop4                             472   472        0  100% /snap/snapd/10707
tmpfs                               254410    22   254388    1% /run/user/1000

7.)Find the ulimit of a user?
core file size          (blocks, -c) unlimited
data seg size           (kbytes, -d) unlimited
scheduling priority             (-e) 0
file size               (blocks, -f) unlimited
pending signals                 (-i) 7606
max locked memory       (kbytes, -l) 65536
max memory size         (kbytes, -m) unlimited
open files                      (-n) 1048576
pipe size            (512 bytes, -p) 8
POSIX message queues     (bytes, -q) 819200
real-time priority              (-r) 0
stack size              (kbytes, -s) unlimited
cpu time               (seconds, -t) unlimited
max user processes              (-u) 7606
virtual memory          (kbytes, -v) unlimited
file locks                      (-x) unlimited

8.)Find the ulimit of the process?
unlimited

9.)Find the file descriptors used by a process?
COMMAND PID     USER   FD      TYPE DEVICE SIZE/OFF  NODE NAME
apache2 823 www-data  cwd       DIR  253,1     4096     2 /
apache2 823 www-data  rtd       DIR  253,1     4096     2 /
apache2 823 www-data  txt       REG  253,1   704520 13813 /usr/sbin/apache2
apache2 823 www-data  mem       REG  253,1   104984  8736 /usr/lib/x86_64-linux-gnu/libgcc_s.so.1
apache2 823 www-data  mem       REG  253,1   239896  8830 /usr/lib/x86_64-linux-gnu/libnss_systemd.so.2
apache2 823 www-data  DEL       REG    0,1          28462 /dev/zero
apache2 823 www-data  mem       REG  253,1    67792 13766 /usr/lib/apache2/modules/mod_mpm_event.so
apache2 823 www-data  mem       REG  253,1    51832  8826 /usr/lib/x86_64-linux-gnu/libnss_files-2.31.so
apache2 823 www-data  mem       REG  253,1    26832 13805 /usr/lib/apache2/modules/mod_status.so
apache2 823 www-data  mem       REG  253,1    39120 13769 /usr/lib/apache2/modules/mod_negotiation.so
apache2 823 www-data  mem       REG  253,1    18640 13796 /usr/lib/apache2/modules/mod_setenvif.so
apache2 823 www-data  mem       REG  253,1    26832 13764 /usr/lib/apache2/modules/mod_mime.so
apache2 823 www-data  mem       REG  253,1    22736 13745 /usr/lib/apache2/modules/mod_filter.so
apache2 823 www-data  mem       REG  253,1    18640 13788 /usr/lib/apache2/modules/mod_reqtimeout.so
apache2 823 www-data  mem       REG  253,1    14544 13741 /usr/lib/apache2/modules/mod_env.so
apache2 823 www-data  mem       REG  253,1   108936  8932 /usr/lib/x86_64-linux-gnu/libz.so.1.2.11
apache2 823 www-data  mem       REG  253,1    14544 13738 /usr/lib/apache2/modules/mod_dir.so
apache2 823 www-data  mem       REG  253,1    39120 13736 /usr/lib/apache2/modules/mod_deflate.so
apache2 823 www-data  mem       REG  253,1    43216 13718 /usr/lib/apache2/modules/mod_autoindex.so
apache2 823 www-data  mem       REG  253,1    14544 13717 /usr/lib/apache2/modules/mod_authz_user.so
apache2 823 www-data  mem       REG  253,1    14544 13715 /usr/lib/apache2/modules/mod_authz_host.so
apache2 823 www-data  mem       REG  253,1    30928 13711 /usr/lib/apache2/modules/mod_authz_core.so
apache2 823 www-data  mem       REG  253,1    14544 13707 /usr/lib/apache2/modules/mod_authn_file.so
apache2 823 www-data  mem       REG  253,1    14544 13704 /usr/lib/apache2/modules/mod_authn_core.so
apache2 823 www-data  mem       REG  253,1    18640 13700 /usr/lib/apache2/modules/mod_auth_basic.so
apache2 823 www-data  mem       REG  253,1    18640 13697 /usr/lib/apache2/modules/mod_alias.so
apache2 823 www-data  mem       REG  253,1    14544 13695 /usr/lib/apache2/modules/mod_access_compat.so
apache2 823 www-data  mem       REG  253,1    18816  8708 /usr/lib/x86_64-linux-gnu/libdl-2.31.so
apache2 823 www-data  mem       REG  253,1    30936  8919 /usr/lib/x86_64-linux-gnu/libuuid.so.1.3.0
apache2 823 www-data  mem       REG  253,1   182560  8720 /usr/lib/x86_64-linux-gnu/libexpat.so.1.6.11
apache2 823 www-data  mem       REG  253,1   202760  8696 /usr/lib/x86_64-linux-gnu/libcrypt.so.1.1.0
apache2 823 www-data  mem       REG  253,1  2029224  8690 /usr/lib/x86_64-linux-gnu/libc-2.31.so
apache2 823 www-data  mem       REG  253,1   157224  8861 /usr/lib/x86_64-linux-gnu/libpthread-2.31.so
apache2 823 www-data  mem       REG  253,1   229248 13632 /usr/lib/x86_64-linux-gnu/libapr-1.so.0.6.5
apache2 823 www-data  mem       REG  253,1   184152 13646 /usr/lib/x86_64-linux-gnu/libaprutil-1.so.0.6.1
apache2 823 www-data  mem       REG  253,1   465008  8845 /usr/lib/x86_64-linux-gnu/libpcre.so.3.13.3
apache2 823 www-data  mem       REG  253,1   191472  8659 /usr/lib/x86_64-linux-gnu/ld-2.31.so
apache2 823 www-data    0r      CHR    1,3      0t0     6 /dev/null
apache2 823 www-data    1w      CHR    1,3      0t0     6 /dev/null
apache2 823 www-data    2w      REG  253,1     1110 14409 /var/log/apache2/error.log
apache2 823 www-data    3u     sock    0,9      0t0 26784 protocol: TCP
apache2 823 www-data    4u     IPv6  26785      0t0   TCP *:http (LISTEN)
apache2 823 www-data    5r     FIFO   0,13      0t0 28461 pipe
apache2 823 www-data    6w     FIFO   0,13      0t0 28461 pipe
apache2 823 www-data    7w      REG  253,1        0 14411 /var/log/apache2/other_vhosts_access.log
apache2 823 www-data    8w      REG  253,1       88 14410 /var/log/apache2/access.log
apache2 823 www-data    9u  a_inode   0,14        0 10385 [eventpoll]
apache2 823 www-data   10r     FIFO   0,13      0t0 26810 pipe
apache2 823 www-data   11w     FIFO   0,13      0t0 26810 pipe

10)Find the 5 processes by memory usage?
top - 17:24:54 up  2:42,  1 user,  load average: 0.03, 0.01, 0.00
Tasks: 120 total,   1 running, 119 sleeping,   0 stopped,   0 zombie
%Cpu(s):  3.2 us,  0.0 sy,  0.0 ni, 96.8 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   1987.6 total,   1492.2 free,    146.3 used,    349.0 buff/cache
MiB Swap:   1757.0 total,   1757.0 free,      0.0 used.   1686.0 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND
    793 root      20   0  775520  25516  15256 S   0.0   1.3   0:01.07 snapd
    895 root      20   0  107884  20932  13292 S   0.0   1.0   0:00.07 unattended-upgr
    785 root      20   0   29068  18152  10504 S   0.0   0.9   0:00.07 networkd-dispat
    661 root      rt   0  280328  18132   8200 S   0.0   0.9   0:00.63 multipathd
    393 root      19  -1   51688  14424  13296 S   0.0   0.7   0:00.16 systemd-journal

11)Find the top 5 processes by cpu usage?
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.5 102376 11800 ?        Ss   14:42   0:01 /sbin/init maybe-ubiquity
root           2  0.0  0.0      0     0 ?        S    14:42   0:00 [kthreadd]
root           3  0.0  0.0      0     0 ?        I<   14:42   0:00 [rcu_gp]
root           4  0.0  0.0      0     0 ?        I<   14:42   0:00 [rcu_par_gp]
root           6  0.0  0.0      0     0 ?        I<   14:42   0:00 [kworker/0:0H-kblockd]

12)Find the top 5 processes by network usage?
Active Internet connections (w/o servers)
Proto Recv-Q Send-Q Local Address           Foreign Address         State       PID/Program name    
Active UNIX domain sockets (w/o servers)
Proto RefCnt Flags       Type       State         I-Node   PID/Program name     Path
unix  2      [ ]         DGRAM                    30019    1135/systemd         /run/user/1000/systemd/notify
unix  3      [ ]         DGRAM                    15785    1/init               /run/systemd/notify
unix  2      [ ]         DGRAM                    15802    1/init               /run/systemd/journal/syslog
unix  8      [ ]         DGRAM                    15810    1/init               /run/systemd/journal/dev-log
unix  9      [ ]         DGRAM                    15814    1/init               /run/systemd/journal/socket
unix  3      [ ]         STREAM     CONNECTED     26725    1/init               /run/systemd/journal/stdout
unix  3      [ ]         DGRAM                    25817    707/systemd-timesyn  
unix  3      [ ]         DGRAM                    25816    707/systemd-timesyn  
unix  3      [ ]         DGRAM                    15786    1/init               
unix  2      [ ]         DGRAM                    25261    749/systemd-resolve  
unix  3      [ ]         STREAM     CONNECTED     26987    771/dbus-daemon      /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     27056    771/dbus-daemon      /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     27158    1/init               /run/systemd/journal/stdout
unix  2      [ ]         DGRAM                    16149    393/systemd-journal  
unix  3      [ ]         DGRAM                    15787    1/init               
unix  3      [ ]         STREAM     CONNECTED     33392    1610/fwupd           
unix  3      [ ]         STREAM     CONNECTED     26729    1/init               /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     27070    785/python3          
unix  3      [ ]         STREAM     CONNECTED     33381    1610/fwupd           
unix  3      [ ]         STREAM     CONNECTED     26247    707/systemd-timesyn  
unix  3      [ ]         STREAM     CONNECTED     26628    771/dbus-daemon      
unix  3      [ ]         STREAM     CONNECTED     26748    1/init               /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     19326    661/multipathd       
unix  3      [ ]         STREAM     CONNECTED     33393    771/dbus-daemon      /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     27727    784/irqbalance       
unix  2      [ ]         DGRAM                    25812    707/systemd-timesyn  
unix  3      [ ]         STREAM     CONNECTED     27071    785/python3          
unix  3      [ ]         STREAM     CONNECTED     28267    794/systemd-logind   
unix  3      [ ]         STREAM     CONNECTED     20260    1/init               /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     26630    1/init               /run/systemd/journal/stdout
unix  2      [ ]         DGRAM                    26643    767/cron             
unix  3      [ ]         STREAM     CONNECTED     27157    895/python3          
unix  3      [ ]         DGRAM                    25815    707/systemd-timesyn  
unix  3      [ ]         STREAM     CONNECTED     26726    1/init               /run/systemd/journal/stdout
unix  3      [ ]         DGRAM                    25814    707/systemd-timesyn  
unix  2      [ ]         DGRAM                    36514    2050/sudo            
unix  3      [ ]         STREAM     CONNECTED     26724    785/python3          
unix  3      [ ]         STREAM     CONNECTED     33383    1/init               /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     27055    785/python3          
unix  3      [ ]         STREAM     CONNECTED     27874    793/snapd            
unix  3      [ ]         STREAM     CONNECTED     24533    707/systemd-timesyn  
unix  2      [ ]         DGRAM                    25935    747/systemd-network  
unix  3      [ ]         STREAM     CONNECTED     24789    1/init               /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     26983    771/dbus-daemon      
unix  3      [ ]         STREAM     CONNECTED     17787    424/systemd-udevd    
unix  3      [ ]         STREAM     CONNECTED     27240    771/dbus-daemon      /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     26245    747/systemd-network  
unix  3      [ ]         STREAM     CONNECTED     26989    771/dbus-daemon      /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     26985    771/dbus-daemon      /run/dbus/system_bus_socket
unix  3      [ ]         DGRAM                    25939    747/systemd-network  
unix  3      [ ]         DGRAM                    25941    747/systemd-network  
unix  2      [ ]         DGRAM                    26982    771/dbus-daemon      
unix  3      [ ]         STREAM     CONNECTED     25258    1/init               /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     26077    749/systemd-resolve  
unix  3      [ ]         DGRAM                    25940    747/systemd-network  
unix  3      [ ]         STREAM     CONNECTED     17796    1/init               /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     26467    767/cron             
unix  3      [ ]         STREAM     CONNECTED     29989    1/init               /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     27239    896/polkitd          
unix  3      [ ]         STREAM     CONNECTED     26392    1/init               
unix  3      [ ]         STREAM     CONNECTED     26642    1/init               /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     29607    1135/systemd         
unix  3      [ ]         DGRAM                    25942    747/systemd-network  
unix  3      [ ]         STREAM     CONNECTED     26984    771/dbus-daemon      
unix  3      [ ]         STREAM     CONNECTED     25538    761/accounts-daemon  
unix  3      [ ]         STREAM     CONNECTED     25400    1/init               /run/systemd/journal/stdout
unix  2      [ ]         DGRAM                    16340    1/init               
unix  2      [ ]         DGRAM                    28126    789/rsyslogd         
unix  3      [ ]         STREAM     CONNECTED     25241    1/init               /run/systemd/journal/stdout
unix  2      [ ]         DGRAM                    29616    1140/(sd-pam)        
unix  3      [ ]         STREAM     CONNECTED     26988    771/dbus-daemon      /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     25239    747/systemd-network  
unix  3      [ ]         STREAM     CONNECTED     25399    761/accounts-daemon  
unix  3      [ ]         STREAM     CONNECTED     27068    771/dbus-daemon      /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     30024    771/dbus-daemon      /run/dbus/system_bus_socket
unix  3      [ ]         DGRAM                    30021    1135/systemd         
unix  3      [ ]         STREAM     CONNECTED     27261    771/dbus-daemon      /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     27067    794/systemd-logind   
unix  3      [ ]         STREAM     CONNECTED     27265    895/python3          
unix  2      [ ]         DGRAM                    27061    794/systemd-logind   
unix  3      [ ]         DGRAM                    30020    1135/systemd         
unix  3      [ ]         STREAM     CONNECTED     26246    749/systemd-resolve  
unix  3      [ ]         STREAM     CONNECTED     27266    895/python3          
unix  3      [ ]         STREAM     CONNECTED     26986    771/dbus-daemon      /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     27260    895/python3          
unix  3      [ ]         DGRAM                    17800    424/systemd-udevd    
unix  2      [ ]         DGRAM                    30010    1135/systemd         
unix  3      [ ]         DGRAM                    17799    424/systemd-udevd    
unix  3      [ ]         STREAM     CONNECTED     30023    1135/systemd         
unix  2      [ ]         DGRAM                    17797    424/systemd-udevd    
unix  2      [ ]         DGRAM                    29151    883/login            

14)Find the network Traffic and bandwidth usage of the machine?
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN mode DEFAULT group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    RX: bytes  packets  errors  dropped overrun mcast   
    20.7k      246      0       0       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    20.7k      246      0       0       0       0       
2: enp0s3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP mode DEFAULT group default qlen 1000
    link/ether 08:00:27:cb:00:db brd ff:ff:ff:ff:ff:ff
    RX: bytes  packets  errors  dropped overrun mcast   
    3.53M      2.90k    0       0       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    157k       1.97k    0       0       0       0       

16)List files opened by a process?
COMMAND  PID  USER   FD   TYPE DEVICE SIZE/OFF   NODE NAME
bash    1145 rohit  cwd    DIR  253,1     4096  10093 /home/rohit/task
bash    1145 rohit  rtd    DIR  253,1     4096      2 /
bash    1145 rohit  txt    REG  253,1  1183448    497 /usr/bin/bash
bash    1145 rohit  mem    REG  253,1    51832   8826 /usr/lib/x86_64-linux-gnu/libnss_files-2.31.so
bash    1145 rohit  mem    REG  253,1    27002 133058 /usr/lib/x86_64-linux-gnu/gconv/gconv-modules.cache
bash    1145 rohit  mem    REG  253,1  3035952  13562 /usr/lib/locale/locale-archive
bash    1145 rohit  mem    REG  253,1  2029224   8690 /usr/lib/x86_64-linux-gnu/libc-2.31.so
bash    1145 rohit  mem    REG  253,1    18816   8708 /usr/lib/x86_64-linux-gnu/libdl-2.31.so
bash    1145 rohit  mem    REG  253,1   192032   8892 /usr/lib/x86_64-linux-gnu/libtinfo.so.6.2
bash    1145 rohit  mem    REG  253,1   191472   8659 /usr/lib/x86_64-linux-gnu/ld-2.31.so
bash    1145 rohit    0u   CHR    4,1      0t0     22 /dev/tty1
bash    1145 rohit    1u   CHR    4,1      0t0     22 /dev/tty1
bash    1145 rohit    2u   CHR    4,1      0t0     22 /dev/tty1
bash    1145 rohit  255u   CHR    4,1      0t0     22 /dev/tty1

17)List Processes listening on a specific port?
tcp6       0      0 :::80                   :::*                    LISTEN      822/apache2         

18)Find the status of the service?
● apache2.service - The Apache HTTP Server
     Loaded: loaded (/lib/systemd/system/apache2.service; enabled; vendor preset: enabled)
     Active: active (running) since Sat 2021-03-06 14:42:36 UTC; 21h ago
       Docs: https://httpd.apache.org/docs/2.4/
   Main PID: 822 (apache2)
      Tasks: 55 (limit: 2281)
     Memory: 8.1M
     CGroup: /system.slice/apache2.service
             ├─822 /usr/sbin/apache2 -k start
             ├─823 /usr/sbin/apache2 -k start
             └─824 /usr/sbin/apache2 -k start

Mar 06 14:42:36 server systemd[1]: Starting The Apache HTTP Server...
Mar 06 14:42:36 server apachectl[783]: AH00558: apache2: Could not reliably determine the server's fully qualified domain name, using 127.0.1.1. Set the 'ServerName' directive globally to suppress this message
Mar 06 14:42:36 server systemd[1]: Started The Apache HTTP Server.

19)Find Zombie processes on a machine?
rohit       4697  0.0  0.0   6300   736 tty1     S+   11:49   0:00 grep --color=auto z

20)Find the eniviornment variables set on machine?
SHELL=/bin/bash
XDG_SEAT=seat0
PWD=/home/rohit/task
LOGNAME=rohit
XDG_SESSION_TYPE=tty
MOTD_SHOWN=pam
HOME=/home/rohit
LANG=en_US.UTF-8
LS_COLORS=rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:
INVOCATION_ID=49a1307c7c7b46b1804d943b955c5610
LESSCLOSE=/usr/bin/lesspipe %s %s
XDG_SESSION_CLASS=user
TERM=linux
LESSOPEN=| /usr/bin/lesspipe %s
USER=rohit
SHLVL=1
XDG_VTNR=1
XDG_SESSION_ID=1
XDG_RUNTIME_DIR=/run/user/1000
JOURNAL_STREAM=9:29060
XDG_DATA_DIRS=/usr/local/share:/usr/share:/var/lib/snapd/desktop
HUSHLOGIN=FALSE
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin
DBUS_SESSION_BUS_ADDRESS=unix:path=/run/user/1000/bus
MAIL=/var/mail/rohit
_=/usr/bin/env
OLDPWD=/home/rohit

21)Display processes started by a user?
[?25l[?1c[H[J[mtop - 12:05:22 up  5:44,  1 user,  load average: 0.00, 0.00, 0.00[m[39;49m[m[39;49m[K
Tasks:[m[39;49m[1m 126 [m[39;49mtotal,[m[39;49m[1m   1 [m[39;49mrunning,[m[39;49m[1m 119 [m[39;49msleeping,[m[39;49m[1m   6 [m[39;49mstopped,[m[39;49m[1m   0 [m[39;49mzombie[m[39;49m[m[39;49m[K
%Cpu(s):[m[39;49m[1m  0.0 [m[39;49mus,[m[39;49m[1m  3.2 [m[39;49msy,[m[39;49m[1m  0.0 [m[39;49mni,[m[39;49m[1m 96.8 [m[39;49mid,[m[39;49m[1m  0.0 [m[39;49mwa,[m[39;49m[1m  0.0 [m[39;49mhi,[m[39;49m[1m  0.0 [m[39;49msi,[m[39;49m[1m  0.0 [m[39;49mst[m[39;49m[m[39;49m[K
MiB Mem :[m[39;49m[1m   1987.6 [m[39;49mtotal,[m[39;49m[1m   1351.4 [m[39;49mfree,[m[39;49m[1m    168.8 [m[39;49mused,[m[39;49m[1m    467.4 [m[39;49mbuff/cache[m[39;49m[m[39;49m[K
MiB Swap:[m[39;49m[1m   1757.0 [m[39;49mtotal,[m[39;49m[1m   1757.0 [m[39;49mfree,[m[39;49m[1m      0.0 [m[39;49mused.[m[39;49m[1m   1656.6 [m[39;49mavail Mem [m[39;49m[m[39;49m[K
[K
[7m    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                      [m[39;49m[K
[m   1135 rohit     20   0   18704   9888   8144 S   0.0   0.5   0:00.05 systemd                      [m[39;49m[K
[m   1140 rohit     20   0  103600   3668      4 S   0.0   0.2   0:00.00 (sd-pam)                     [m[39;49m[K
[m   1145 rohit     20   0    8396   5512   3684 S   0.0   0.3   0:00.63 bash 

22.)kill a process
sudo kill -s 15 PID-HERE

23)List Open Port
Starting Nmap 7.80 ( https://nmap.org ) at 2021-03-07 12:29 UTC
Nmap scan report for localhost (127.0.0.1)
Host is up (0.000063s latency).
Not shown: 999 closed ports
PORT   STATE SERVICE
80/tcp open  http

Nmap done: 1 IP address (1 host up) scanned in 0.04 seconds

24)Find the permission set for a file
-rw-rw-r-- 1 rohit rohit 35762 Mar  7 14:42 task.txt

25)list all the directiories inside a directory
.
└── test

1 directory

26)Display number of files in the directory?
3

27)Display number of lines in a file?
499 task.txt

28)List the oldest and newest file in a directory ? 
total 48
-rw-rw-r-- 1 rohit rohit   216 Mar  7 15:28 task.cc
-rw-rw-r-- 1 rohit rohit   426 Mar  7 08:03 p-io-adv

29)Display the OS and kernel information ? 
Linux version 5.4.0-66-generic (buildd@lgw01-amd64-039) (gcc version 9.3.0 (Ubuntu 9.3.0-17ubuntu1~20.04)) #74-Ubuntu SMP Wed Jan 27 22:54:38 UTC 2021

30)Display the sizing (cpu cores, memory, and disk) of the machine?
  *-core
       description: Motherboard
       product: VirtualBox
       vendor: Oracle Corporation
       physical id: 0
       version: 1.2
       serial: 0
 *-memory
          description: System memory
          physical id: 1
          size: 2GiB
 *-disk
             description: ATA Disk
             product: VBOX HARDDISK
             physical id: 0.0.0
             bus info: scsi@5:0.0.0
             logical name: /dev/sdd
             version: 1.0
             serial: 1RKsba-Mvv0-6AeI-9WCa-HWpt-GJs5-ZnRDkS
             size: 10GiB
             capacity: 10GiB
             capabilities: lvm2
             configuration: ansiversion=5 logicalsectorsize=512 sectorsize=512
