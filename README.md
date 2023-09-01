# Dumbphone

Convert to your smartphone to a dumb(ish) phone


## Prerequisites

* Backup all essential data on your phone.
* Be familiar with your phone settings.
* Prepare a list of apps you want to uninstall, noting their full package names. If you're unsure, "Full Package Names" on F-Droid can assist.

## Steps

* Go to your phone settings and enable developer mode.
* Activate USB debugging.
* Connect your phone to your laptop.
* Run `./dumbify` with your list of apps to uninstall. This script will identify these apps, create backups on your computer, and then remove them from your phone, while preserving app data.
* When you need your phone's advanced features again, simply run `./smartify` to restore.

