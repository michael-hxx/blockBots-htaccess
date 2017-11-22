# blockBots-htaccess
Blocking bots with htaccess


## Blocking bots with fail2ban is the better solution if you want to block many bots. A large htaccess could increase your site load.
Use Fail2ban together with this filter:
https://github.com/michael-hxx/Fail2Ban-Filter/blob/master/filter.d/apache-badbots.conf
