# Steemit-Pending-Payouts-Checker-PHP

Name: Steem Pending Payout Checker 
Contributors: akintunde & oguzdelioglu {github usernames}
Programmed with: PHP
Requires at least: php 5.6 
Major Dependency: Steemjs API
License: APACHE LICENSE
License URI: https://www.apache.org/licenses/LICENSE-2.0
APP Address: check.akin.com.ng

## Short Summary:
This script calculates the pending payout of steem blockchain users.It can tested in the app address provided above.

## Description:
This script helps to solve the ambiguity associated with knowing the expected payout of a user at any 7 day period which is the interval of payment for every comment or post made on steemit.com, utopian-io, busy.org, zappl and the rest of the apps that use the steem blockchain.

If you don't know about the steem blockchain , you can read about it [here](https://steem.io/).

This script was forked from another script by [oguzdelioglu](https://github.com/oguzdelioglu/). 

How to it works:
The Script has an index page that has a form as shown below:

![Preview](https://check.akin.com.ng/a.png)

Users will have to fill this form with their steem username, submit and then they will be directed to the action page (result.php) where the script will link the steemjs api to bring in all their posts details including resteemed posts, then generate a table containing all  the generated details in a ordere form while their sbd payouts gets added up as shown below;

![Preview](http://check.akin.com.ng/b.png)

The script also  has an htaccess file that processes the fancy url to allow users use an address like this (check.akin.com.ng/@akintunde) or (check.akin.com.ng/akintunde). This depends on the domain name that this script uses.

The htaccess file also helps tells the server to process files with .php and .html as php files.This is necessary for servers that doesnt have this set by default

The htaccess also locks the index page to index.php





== Installation ==

1. Download this script as a zip file (from the github page https://github.com/Akintunde102/Steemit-Pending-Payouts-Checker-PHP)
2. Copy to your server  www (or htdocs) folder
3. That's it 
4. Just view from your server domain name (or from localhost if you are in a local environment)


== Changelog ==

= 1.0 =
Initial Version

Contact me :
Discord: @akintunde
email: jegedeakintunde[at]gmail.com
utopian: @akintunde
github; @akintunde102


 

