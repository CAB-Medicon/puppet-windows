## 2.0.0-beta (2025-04-11)

Fork 1.0.6 and incorporated all changes in other forks that where not already part of 1.0.6.



These are:

 * Breeze773/puppet-windows

 * cmchoi2000/puppet-windows

 * akomakom/puppet-windows

 * Vizibirka/puppet-windows

Thank you.

I will now try to take over and release a stable version of all your changes for Puppet 8 and onwards.

## 1.0.6 (8/13/2017)

BUG FIXES:

 * Fix kernel version comparison (@rogerlz)

## 1.0.5 (8/5/2017)

BUG FIXES:
 * Fix regex validation of update time (@makomatic)
 * Fix for newer versions of windows update service (@rogerlz)

## 1.0.4 (10/15/2016)

IMPROVEMENTS:
* Allow newer versions of puppetlabs/powershell.

## 1.0.3 (06/07/2016)

IMPROVEMENTS:
* Allow arbitrary shortcut link targets (to support URLs and shell objects)

## 1.0.2 (08/28/2015)

IMPROVEMENTS:
* Updated default Java version to 8u60.

## 1.0.1 (08/17/2015)

IMPROVEMENTS:
* Updated default Java version to 8u51.

## 1.0.0 (06/17/2015)

BUG FIXES:
* Fixed disabling screen saver via @etlweather (GH-4)
* Add support for Java 8 via Aloysius Lim (GH-5)
* Fix linting issues.

FEATURES:
* Added the `windows::power_scheme` class.
* Added `$windows::java::home` variable.
* Allow customization of icon in `windows::shortcut`.
