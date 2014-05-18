Munstrap
========

Alternative Munin 2.x templates based on Twitter Bootstrap 3


Installation
------------

```
cd /etc/munin

git clone https://github.com/jonnymccullagh/munstrap.git
mv -b munstrap/templates .
mv -b munstrap/static .
rm -rf munstrap

cd /var/www/munin
rm -rf /var/www/munin/*
```

Upgrades
---------
```
cd /etc/munin/munstrap
git pull
```

Revert to stock
---------------
```
cd /etc/munin
rm -rf templates static
mv templates~ templates
mv static~ static
```
