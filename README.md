DEVONthink Search Alfred 2 Workflow
==================================

Features
--------

This workflow allows you to search your DEVONthink documents from within Alfred. It supports DEVONthink Personal as well as DEVONthink Pro (with multiple databases)

Installation
------------

[Download](http://bit.ly/18s4R1b) and import into Alfred 2.

Usage
-----

### Keywords

* **`devon [your search string]`** - Search in all databases

![](https://dl.dropboxusercontent.com/u/5453663/devon.png)

* **`devondb [your search string]`** - Search in specific database

![](https://dl.dropboxusercontent.com/u/5453663/devondb1.png)
![](https://dl.dropboxusercontent.com/u/5453663/devondb2.png)

* **`devondb!`** - Refresh database list

The association between database names and uuids can only be obtained via AppleScript. This is done automatically if you run the `devondb` command for the first time. The information is then cached for better performance. If you add a new DEVONthink database later on, you'll have to run the `devondb!` command to refresh the database list.

![](https://dl.dropboxusercontent.com/u/5453663/devondb!.png)