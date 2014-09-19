vuze-systemd
============

# Vuze Service Script for systemd

## vuze.service
* systemd service file
* change user/group to match your system
* change EnviornmentFile to point to location of vuze variable file
  * settings are stored in the users home directory under .azureus

## vuze
* variable file to put in /etc/default or /etc/sysconfig
* modify to point to Azureus jar file
* Make any additional Java or Azureus changes
  * See http://wiki.vuze.com/w/Commandline_options#Console_UI_Options for additional command line options

## Requirements
Console UI version of Azureus requires the following libraries in the same directory as the Azureus jar file
* commons-cli.jar
* junit.jar
* log4j.jar

Download from: http://svn.vuze.com/public/client/trunk/uis/lib/
