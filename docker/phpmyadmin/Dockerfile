FROM phpmyadmin/phpmyadmin

RUN echo "\$cfg['LoginCookieValidity'] = 60*60*24*7*365; // Login for 1 year." >> /etc/phpmyadmin/config.inc.php
RUN echo "ini_set('session.gc_maxlifetime', \$cfg['LoginCookieValidity']);" >> /etc/phpmyadmin/config.inc.php
