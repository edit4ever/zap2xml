# zap2xml
zap2xml in Python 2.7 for use on LibreELEC/Openelec Kodi -- the zap2xml.py file can be used on other installations.

See the README.md file in the Kodi folder for instructions on building the addon.




crontab entry

min(0 - 59) hour(0 - 23) day of month(1 - 31) month(1 - 12) day of week(0 - 6)(Sunday=0)  command to be executed

crontab -e example

0 2 * * 0,3 /usr/bin/python /storage/downloads/zap2xml/zap2xml.py

Every 2 am on Sunday and Wednesday
