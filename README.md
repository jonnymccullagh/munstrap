Munstrap
========

Alternative Munin 2.x templates based on Twitter Bootstrap

Installation
------------

```
cd /etc/munin
mv ./templates ./templates_default
mv ./static ./static_default
git clone https://github.com/Rauks/munstrap.git
mv ./munstrap/templates .
mv ./munstrap/static .
cd /var/www/html/munin
mv static /etc/munin/static_old
rm -rf /var/www/html/munin/*
cp -R /etc/munin/static /var/www/html/munin
chown -R munin:munin /var/www/html/munin/static
```
