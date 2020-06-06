# TraccarFail2Ban

#### Installation
1. Copy the filter configuration file `traccar.conf` to `/etc/fail2ban/filter.d`
2. Append the jail config from `traccar.jail` to fail2ban
3. Restart fail2ban `systemctl restart fail2ban`

#### Notes for traccar.jail
The jail assumes, that all known data ports for traccar are used - adjust if needed.   
The jail assumes, that the default log path under `/opt/traccar/logs/` is used by traccar.
