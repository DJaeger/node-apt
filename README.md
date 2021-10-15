[![Build Status](https://travis-ci.org/mrvisser/node-apt.png?branch=master)](https://travis-ci.org/mrvisser/node-apt) [![NPM version](https://badge.fury.io/js/apt.png)](http://badge.fury.io/js/apt)

A node.js wrapper for aptitude package management. Supports the following operations:

### Update

Uses `apt-get update` to update the local apt cache

### Show

Uses `dpkg -s` to parse some data about a named package

### Install

Uses `apt-get install -y` to install a package

### Uninstall

Uses `apt-get remove -y` to remove a package

### Autoremove

Uses `apt-get autoremove -y` to remove obsolete packages

### Upgrade

Uses `apt-get upgrade -y` to upgrade packages
