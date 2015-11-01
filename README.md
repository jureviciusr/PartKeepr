[![PartKeepr](https://partkeepr.org/images/partkeepr-banner.png)](https://www.partkeepr.org)

[![JSON-LD enabled](http://json-ld.org/images/json-ld-button-88.png)](http://json-ld.org)
[![Build Status](https://travis-ci.org/partkeepr/PartKeepr.svg?branch=sf2migration)](https://travis-ci.org/partkeepr/PartKeepr)
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/a9f5bdce-ac86-4c51-b87d-56fd0f241155/mini.png)](https://insight.sensiolabs.com/projects/a9f5bdce-ac86-4c51-b87d-56fd0f241155)
[![Code Climate](https://codeclimate.com/github/partkeepr/PartKeepr/badges/gpa.svg)](https://codeclimate.com/github/partkeepr/PartKeepr)
[![Test Coverage](https://codeclimate.com/github/partkeepr/PartKeepr/badges/coverage.svg)](https://codeclimate.com/github/partkeepr/PartKeepr/coverage)
[![Dependency Status](https://www.versioneye.com/user/projects/559e71d36166340022000e57/badge.svg?style=flat)](https://www.versioneye.com/user/projects/559e71d36166340022000e57)

PartKeepr is an [inventory management software](https://en.wikipedia.org/wiki/Inventory_management_software), primarily
designed for electronic components.

PartKeepr is written in **PHP** and using the [**Symfony2**](http://symfony.com) framework.

Demo Site
---------

To test everything which has been written so far, please visit http://demo.partkeepr.org for a demo which is built from
the git sources once an hour.

Requirements
------------

PartKeepr needs:

* PHP 5.6 and up. Some distributions don't have PHP 5.6 yet, but [provide packages](documentation/installation/php56.md). 
* A MySQL or PostgreSQL database

Installation from zip file
--------------------------

Simply point your browser to `web/setup/index.html` and the installer will start.

Installation from GIT
---------------------

Clone the repository, copy `app/config/parameters.php.dist` to `app/config/parameters.php`, install [composer](https://getcomposer.org/download/), run `composer install` and then point your browser to `web/setup/index.html`

Thanks
------

A very big "thank you" goes out to Georgyo of NYC resistor - although he claimed that he isn't creative, he invented the
name "PartKeepr" which eventually became the project's name.
