# icinga2_bbb_stats

1: enable api on BBB server
2: put the perl script to icinga2 plugin folder
3: create icinga2 check command ( Check Big Blue Button Statistics )
   ./check_bbb_stats --host=$assress$ --secret=[api key] --protocol=[http | https ]
4: put the ini file to your icingaweb2-module-graphite template folder

