TASK WEEK#1\
1.)Find the Processes running on a linux machine?
`rohit@server:~ ps -aux`
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
