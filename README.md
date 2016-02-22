# CMScheck
A bash script to find outdated CMS installs

Example output:
[root@someserver CMScheck]# ./CMScheck

What is the base Document root where all vhosts are found?
/var/www/vhosts

+-----------------------------------------+
|    Wordpress current version:  4.4.2    |
|    Joomla current version:     3.4      |
|    Druapl current version:     8.0.3    |
+-----------------------------------------+

Looking for Wordpress installs in /var/www/vhosts...
/var/www/vhosts/domain1.com/httpdocs/wp-includes/version.php:$wp_version = '3.4.1';
/var/www/vhosts/domain2.com/private/httpdocs/rss/wp-includes/version.php:$wp_version = '3.8.4';

Looking for Joomla installs in /var/www/vhosts...
/var/www/vhosts/domain3.com/httpdocs/libraries/cms/version/version.php = 3.1.5
/var/www/vhosts/domain4.com/httpdocs/libraries/joomla/version.php = 1.5.15

Looking for Drupal installs in /var/www/vhosts...
None found

