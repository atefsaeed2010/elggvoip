# Introduction #

THis is a simple plugin for integrate Elgg with A2billing and asterisk. You can help in the code . We need the next feature for new versions:
1. Register automatic the username from Elgg to A2billing
any other features are Welcome


# Details #

**First you install that pluin you need to install a2billing and asterisk please see in http://a2billing.org**

1.- Copy the directory "voip\_chat" inside your directory mods
2.  Copy the directory "customer" in the root of elgg
3.- go to the directory "customer" and edit config.php
change: //  Absolute path to index.php **WITH** trailing slash
define('_DIR\_HOME', '/var/www/vhosts/default/htdocs/callshop/');
and put your absolute path
4.- go to "customer/config" and  edit config.php  and edit in
// Main
$cfg['main']['sitename'] = 'iVoS IPSTAR SUBSCRIBER PORTAL';   // Site Name_

// DB Access
$cfg['db']['host'] = 'localhost';   // Hostname
$cfg['db']['user'] = 'dbuser'; // User
$cfg['db']['pwd'] = 'dbpass';  // Password
$cfg['db']['base'] = 'dbname'; // DB

for your a2billing use and a2billing password and database name

5.- Enabled the pluing in your elgg administration.