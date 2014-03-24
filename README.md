munstrap
========

Alternative Munin 2.x templates based on Twitter Bootstrap 3


Installation
------------
```
cd /etc/munin
git clone https://github.com/Rauks/munstrap.git
mv templates templates.dist
mv static static.dist
ln -s munstrap/templates 
ln -s  munstrap/static 
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
rm templates static
mv templates.dist templates
mv static static.dist
```
