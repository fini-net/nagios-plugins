# nagios-plugins server configs

These are server configs for the nagios-plugins collection.

## Missing configs 

These plugins do not have any representation in the server configs yet:

* check_clamd
* check_cluster
* check_file_age
* check_icmp
* check_ide_smart
* check_ircd
* check_jabber
* check_log
* check_nagios
* check_nntps
* check_ntp_time
* check_oracle
* check_overcr
* check_sensors
* check_swap
* check_ups
* check_uptime
* check_wave

## Check to config map

These checks appear in these configs:

* `check_apt` -> `apt.cfg`
* `check_breeze` -> `breeze.cfg`
* `check_by_ssh` -> `disk.cfg`
* `check_dhcp` -> `dhcp.cfg`
* `check_dig` -> `dns.cfg`
* `check_disk` -> `disk.cfg` `disk-smb.cfg`
* `check_disk_smb` -> `disk-smb.cfg`
* `check_dns` -> `dns.cfg`
* `check_dummy` -> `dummy.cfg`
* `check_flexlm` -> `flexlm.cfg`
* `check_fping` -> `fping.cfg`
* `check_ftp` -> `ftp.cfg`
* `check_http` -> `http.cfg`
* `check_ifoperstatus` -> `ifstatus.cfg`
* `check_ifstatus` -> `ifstatus.cfg`
* `check_imap` -> `mail.cfg`
* `check_load` -> `load.cfg`
* `check_mailq` -> `mailq.cfg`
* `check_mrtg` -> `mrtg.cfg`
* `check_mrtgtraf` -> `mrtg.cfg`
* `check_nntp` -> `news.cfg`
* `check_nt` -> `nt.cfg`
* `check_ntp` -> `ntp.cfg`
* `check_ntp_peer` -> `ntp.cfg`
* `check_nwstat` -> `netware.cfg`
* `check_ping` -> `ping.cfg`
* `check_pop` -> `mail.cfg`
* `check_procs` -> `procs.cfg`
* `check_real` -> `real.cfg`
* `check_rpc` -> `rpc-nfs.cfg`
* `check_simap` -> `mail.cfg`
* `check_smtp` -> `mail.cfg`
* `check_spop` -> `mail.cfg`
* `check_ssh` -> `ssh.cfg`
* `check_ssmtp` -> `mail.cfg`
* `check_tcp` -> `tcp_udp.cfg` `telnet.cfg`
* `check_time` -> `ntp.cfg`
* `check_udp` -> `tcp_udp.cfg`
* `check_users` -> `users.cfg`
